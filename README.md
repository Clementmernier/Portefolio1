# Portfolio de Clément MERNIER GARAND

Ce portfolio est un site web statique présentant mon profil, mes compétences et mes réalisations.

## Technologies Utilisées

- HTML5
- CSS3 (avec animations et design responsive)
- JavaScript (vanilla)
- Font Awesome pour les icônes
- Google Fonts (Poppins)

## Fonctionnalités

- Design responsive
- Animations au défilement
- Menu hamburger pour mobile
- Sections interactives
- Défilement fluide
- Effet de frappe pour le sous-titre
- Cartes animées pour les compétences et expériences

## Structure du Projet

```
portfolio-clement/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── main.js
└── README.md
```

## Déploiement sur GitHub Pages

1. Créez un nouveau repository sur GitHub
2. Initialisez Git dans le dossier du projet :
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   ```
3. Liez votre repository local à GitHub :
   ```bash
   git remote add origin https://github.com/Clementmernier/portfolio.git
   git branch -M main
   git push -u origin main
   ```
4. Allez dans les paramètres du repository sur GitHub
5. Dans la section "GitHub Pages", sélectionnez la branche "main" comme source
6. Votre site sera accessible à l'adresse : https://clementmernier.github.io/portfolio

## Développement Local

Pour travailler sur le site localement, vous pouvez utiliser un serveur local simple :

```bash
# Si vous avez Python installé
python -m http.server 8000

# Si vous avez Node.js installé
npx serve
```

Puis ouvrez votre navigateur à l'adresse `http://localhost:8000`

## Personnalisation

- Les couleurs peuvent être modifiées dans le fichier `css/style.css` en changeant les variables CSS dans `:root`
- Les animations peuvent être ajustées dans le fichier `js/main.js`
- Le contenu peut être modifié directement dans `index.html`

## Contact

- Email : clem.mernier@gmail.com
- GitHub : [@Clementmernier](https://github.com/Clementmernier)
