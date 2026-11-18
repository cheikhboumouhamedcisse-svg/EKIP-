# EKIP — Sauvegarde officielle du projet

## Présentation
EKIP est l’écosystème numérique qui conçoit, possède, développe et pilote ses projets et applications assistés par l’intelligence artificielle. Il réunit des services numériques, des espaces utilisateurs et professionnels, des outils de gestion et des automatisations dans une expérience cohérente.

Les projets rattachés à l’écosystème comprennent notamment **EKIPCINEMA IA**, **ROCSA** et les autres applications développées ou exploitées sous l’identité EKIP.

## Mission de ce dépôt
Ce dépôt GitHub sert de point de sauvegarde versionné et de référence technique pour EKIP. Il a pour objectifs de :
- préserver le code source et la documentation du projet ;
- conserver l’historique des évolutions grâce aux commits Git ;
- faciliter la maintenance, les tests, la restauration et les futurs déploiements ;
- documenter les décisions techniques et les versions validées ;
- réduire les risques de perte de travail lors des évolutions du projet.

## Principes de conservation
- Préserver l’identité, le design, les fonctionnalités et les données existantes lors des améliorations.
- Effectuer des changements progressifs, contrôlés et vérifiables.
- Ne jamais remplacer ou supprimer des données sans sauvegarde et validation.
- Documenter les modifications importantes avec des commits explicites.
- Vérifier les tests et le déploiement avant toute mise en production.

## Propriété intellectuelle et droits
**EKIP conserve et revendique tous les droits qu’il détient sur son identité, ses marques, ses concepts, ses développements originaux, son code source, ses applications, sa documentation et les éléments créés pour son écosystème**, notamment EKIPCINEMA IA et ROCSA, sous réserve des droits de tiers et des contrats applicables.

La présence d’un élément dans ce dépôt ne constitue pas une cession de droits ni une autorisation générale de copie, de redistribution, de réutilisation ou d’exploitation commerciale. Les bibliothèques, modèles, services et composants tiers restent soumis à leurs propres licences et conditions.

## Sécurité — règle impérative
- Ne jamais committer de clés API, mots de passe, jetons d’accès, secrets Supabase, identifiants de paiement ou fichiers `.env` réels.
- Stocker les secrets dans un gestionnaire sécurisé ou dans les variables d’environnement protégées des plateformes concernées.
- Utiliser uniquement des valeurs fictives dans `.env.example`.
- Limiter les accès GitHub aux personnes autorisées et activer les protections adaptées.
- Examiner les changements avant chaque commit et chaque déploiement.

## Stratégie de sauvegarde recommandée
1. Vérifier l’état du projet et les changements à conserver.
2. Exclure secrets, caches, dépendances générées et fichiers temporaires.
3. Créer un commit identifiable décrivant précisément la modification.
4. Synchroniser le dépôt distant.
5. Conserver une seconde copie indépendante et sécurisée des éléments critiques.
6. Sauvegarder séparément les bases de données, fichiers utilisateurs et médias qui ne sont pas versionnés dans Git.
7. Tester périodiquement la restauration à partir d’une version connue.

## État et limites de cette sauvegarde
Ce dépôt et ce document définissent la vocation de la sauvegarde EKIP. **Ils ne prouvent pas à eux seuls que l’intégralité du code applicatif, des bases de données, des fichiers médias, des secrets ou des paramètres de déploiement est déjà sauvegardée.** La couverture doit être contrôlée élément par élément. GitHub ne doit pas être considéré comme l’unique copie de sécurité.

---
**EKIP — Propriété, développement et gouvernance de l’écosystème.**