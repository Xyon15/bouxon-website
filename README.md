# Bouxon — Site web du restaurant

Un site statique simple pour présenter le menu du restaurant en plusieurs langues. La page d’accueil permet de choisir la langue, puis redirige vers le menu correspondant.

## Aperçu des pages
- **index.html**: page d’accueil avec sélection de la langue (Français, Español, English)
- **menu-fr.html / menu-es.html / menu-en.html**: pages du menu par langue
- **style.css**: feuilles de styles globales
- **logo-menu.png**: logo affiché dans l’en-tête
- **carte.txt**: ressource texte (facultative selon vos usages)

## Arborescence
```text
.
├── index.html
├── menu-fr.html
├── menu-es.html
├── menu-en.html
├── style.css
├── logo-menu.png
├── carte.txt
└── .gitignore
```

## Prérequis
- Aucune dépendance côté serveur : site 100% statique
- Un navigateur récent suffit pour l’ouvrir en local

## Lancer en local
1. Ouvrez le fichier `index.html` dans votre navigateur (double-clic depuis l’explorateur de fichiers)
2. Optionnel (recommandé) : utilisez un serveur local (par ex. l’extension "Live Server" de VS Code) pour bénéficier du rechargement automatique

## Déploiement
- Déployez sur n’importe quel hébergeur statique (GitHub Pages, Netlify, Vercel, ou votre propre serveur web)
- Le point d’entrée est `index.html`
- Copiez l’ensemble des fichiers à la racine de l’hébergement

## Modifier le contenu
- **Mettre à jour un menu**: éditez `menu-fr.html`, `menu-es.html` ou `menu-en.html`
- **Adapter le style**: modifiez `style.css`
- **Changer le logo**: remplacez `logo-menu.png` (conservez le même nom de fichier ou mettez à jour la référence dans le HTML)

## Ajouter une nouvelle langue
1. Dupliquez une page de menu existante (ex. `menu-en.html` → `menu-it.html`)
2. Traduisez le contenu de la nouvelle page
3. Dans `index.html`, ajoutez une nouvelle "carte de langue" (un lien) vers `menu-it.html` avec un libellé et, si souhaité, un drapeau SVG

## Accessibilité et bonnes pratiques
- Fournissez des attributs `alt` pertinents pour les images
- Gardez des contrastes suffisants et utilisez des balises sémantiques (`header`, `main`, `section`)
- Utilisez `lang` sur la balise `html` pour chaque page locale (déjà en place)

## SEO minimal
- Vérifiez les balises `<title>` et éventuelles meta descriptions par page
- Servez le site via HTTPS si possible

## Crédits
- Développement: Xyon et Antonfcs (mention dans le code)

## Licence
- Non spécifiée. Ajoutez un fichier de licence si nécessaire.