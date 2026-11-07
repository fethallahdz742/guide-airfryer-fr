# Le Guide Airfryer — version 1

Site éditorial statique en français, conçu pour être léger, responsive et déployable sur Cloudflare Pages.

## Fichiers
- `index.html` : accueil
- `guide-capacite.html` : guide de choix de capacité
- `guide-entretien.html` : guide de nettoyage
- `guide-encombrement.html` : guide pour petite cuisine
- `mentions-legales.html`, `divulgation-affiliation.html`, `confidentialite.html` : pages modèles à compléter
- `styles.css` : styles
- `script.js` : menu mobile et année automatique

## Déploiement Cloudflare Pages depuis GitHub
1. Crée un dépôt GitHub.
2. Téléverse les fichiers du dossier du projet à la racine du dépôt.
3. Dans Cloudflare Dashboard, ouvre **Workers & Pages** et crée une application Pages connectée à Git.
4. Sélectionne le dépôt.
5. Pour un site statique sans étape de compilation, configure :
   - Framework preset : `None` (ou équivalent)
   - Build command : laisser vide si l'interface l'autorise
   - Build output directory : `/` ou le répertoire racine proposé par l'interface. Si Cloudflare exige un répertoire de sortie, consulte son interface actuelle et suis le chemin recommandé pour un projet statique.
6. Déploie, puis vérifie la page d'accueil et chaque lien sur téléphone.

## Avant publication commerciale
- Compléter les pages légales avec des informations exactes.
- Vérifier les conditions des programmes d'affiliation et l'éligibilité du pays de résidence.
- Ajouter uniquement des liens autorisés et les signaler clairement.
- Vérifier les caractéristiques des produits avec les sources officielles.
- Ne pas inventer de tests, prix, avis ou notes.
- Cette version n'a pas de base de données, de formulaire, d'API IA ni de publication automatique.

## Limite de cette V1
C'est un prototype statique. L'automatisation de rédaction quotidienne nécessite une étape séparée (API d'IA, stockage, planification, protection anti-abus et contrôle qualité) et peut engendrer des frais. Ne publiez pas automatiquement des contenus non vérifiés.
