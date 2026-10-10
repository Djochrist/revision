# Revise — parcours de révision

Site statique francophone pour réviser les **bases de données** (avec les commandes SQL d’Oracle comme outil de pratique) et la création/gestion d’entreprise.

## Démarrage

Ouvrir `index.html` dans un navigateur ou publier le dossier complet sur un hébergement statique (GitHub Pages, Netlify, Vercel ou équivalent). Aucun framework, installation, compilation ni serveur applicatif n'est nécessaire.

## Interface et organisation

L’interface suit une logique de parcours d’apprentissage par niveaux : barre supérieure compacte, navigation latérale sur les pages de cours, modules numérotés, exercices à valider et progression visible. La typographie système, les onglets, les bordures sobres et les blocs de code reprennent les conventions visuelles des plateformes de documentation et de formation pour développeurs, en s'inspirant de l'organisation « pathways / seasons / levels » du dépôt Secure Code Game fourni comme référence.

## Contenu

- Accueil Revise avec deux parcours : Bases de données et Création & gestion d’entreprise.
- Bases de données : préparation guidée du TP, 7 tâches du TP initial, 7 leçons, projets progressifs, QCM de théorie et de subtilités, glossaire. Les commandes SQL Oracle sont utilisées dans les exercices pratiques.
- Gestion d'entreprise : 5 chapitres, explications développées et QCM commentés.
- Points, validation d'activités, brouillons, progression sauvegardée localement, remise à zéro.
- Crédit en pied de page : « Developed by djochristk ».

## Données et sauvegarde

La progression utilise le stockage local du navigateur, avec un repli sur un cookie de première partie lorsque c'est possible. Aucune donnée n'est envoyée à un serveur. La sauvegarde peut être limitée lors d'une ouverture directe en `file://`; pour une sauvegarde fiable entre les visites, publier le dossier en HTTPS ou sur un hébergement statique.

## À noter

La vérification SQL côté navigateur repère les composants essentiels d'une requête, mais n'exécute pas SQL dans Oracle. Les requêtes doivent être exécutées dans Oracle APEX pour confirmer leur syntaxe et leurs résultats.
