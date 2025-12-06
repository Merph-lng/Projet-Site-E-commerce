# ArtéNova Shop 🛍️

Une boutique e-commerce moderne spécialisée dans les vêtements et accessoires de mode.

## 📋 Table des matières

- [Aperçu](#aperçu)
- [Technologies utilisées](#technologies-utilisées)
- [Structure du projet](#structure-du-projet)
- [Installation](#installation)
- [Développement](#développement)
- [Fonctionnalités](#fonctionnalités)
- [Captures d'écran](#captures-décran)
- [Roadmap](#roadmap)
- [Contribution](#contribution)
- [Licence](#licence)

##  Aperçu

ArtéNova Shop est une plateforme e-commerce permettant aux utilisateurs de découvrir et acheter des articles de mode tendance. Le site propose une expérience utilisateur fluide avec une navigation intuitive et un design moderne.

**Démo en direct :** [artenova-shop.github.io](https://mon-username.github.io/artenova-shop)

##  Technologies utilisées

### Frontend
- HTML5
- CSS3 (avec variables CSS)
- JavaScript ES6+

### Outils de développement
- Git & GitHub
- VS Code
- Live Server (pour le développement local)

### Prochaines étapes (Roadmap technique)
- [ ] Intégration d'un framework CSS (Tailwind ou Bootstrap)
- [ ] Migration vers React.js
- [ ] Backend avec Node.js/Express
- [ ] Base de données MongoDB
- [ ] Authentification JWT

##  Structure du projet 📁

```
artenova-shop/
│
├── assets/
│   ├── images/
│   │   ├── products/
│   │   │   ├── adidas-camps.jpg
│   │   │   ├── air-force-one.jpg
│   │   │   └── chemise-plissee.jpg
│   │   ├── hero/
│   │   │   └── banner.jpg
│   │   └── logo.png
│   │
│   ├── styles/
│   │   ├── main.css
│   │   ├── header.css
│   │   ├── footer.css
│   │   ├── products.css
│   │   └── variables.css
│   │
│   └── scripts/
│       ├── main.js
│       ├── cart.js
│       └── newsletter.js
│
├── pages/
│   ├── products.html
│   ├── cart.html
│   ├── about.html
│   └── contact.html
│
├── index.html
├── README.md
├── .gitignore
└── LICENSE
```

##  Installation

### Prérequis
- Un navigateur web moderne (Chrome, Firefox, Safari, Edge)
- Un éditeur de code (VS Code recommandé)
- Git installé sur la machine

### Étapes d'installation

1. **Cloner le repository**
```bash
git clone https://github.com/mon-username/artenova-shop.git
cd artenova-shop
```

2. **Ouvre le projet**
```bash
code .
```

3. **Lance un serveur local**
   - Avec VS Code : Installer l'extension "Live Server" en cliquant sur "Go Live"
   - Avec Python : `python -m http.server 8000`
   - Avec Node.js : `npx http-server`

4. **J'accéde au site**
   - J'Ouvre `http://localhost:5500` (ou le port indiqué)

## 💻 Développement

### Organisation du code

- **HTML** : Fichiers séparés par page dans `/pages`
- **CSS** : Fichiers modulaires dans `/assets/styles`
- **JavaScript** : Scripts séparés par fonctionnalité dans `/assets/scripts`

### Conventions de nommage

- **Classes CSS** : kebab-case (ex: `.product-card`)
- **IDs** : camelCase (ex: `#headerNav`)
- **Fichiers** : kebab-case (ex: `product-list.html`)
- **Variables JS** : camelCase (ex: `cartItems`)

### Commits Git

Format recommandé :
```
type(scope): description courte

[feat] Ajout du panier d'achat
[fix] Correction du responsive sur mobile
[style] Amélioration du design du header
[docs] Mise à jour du README
[refactor] Restructuration du code CSS
```

##  Fonctionnalités

### Actuelles
- ✅ Page d'accueil avec produits vedettes
- ✅ Navigation responsive
- ✅ Footer avec newsletter
- ✅ Design moderne et épuré

### En développement
- 🚧 Page produits avec filtres
- 🚧 Panier d'achat fonctionnel
- 🚧 Système de recherche
- 🚧 Formulaire de contact

### À venir
- 📋 Authentification utilisateur
- 📋 Paiement en ligne
- 📋 Suivi de commande
- 📋 Espace client
- 📋 Système d'avis clients

##  Captures d'écran

*(À ajouter après avoir des visuels)*

##  Roadmap

### Phase 1 - Fondations (Actuelle)
- [x] Structure HTML de base
- [x] Styles CSS basiques
- [ ] Amélioration du responsive
- [ ] Optimisation des images

### Phase 2 - Fonctionnalités
- [ ] Panier d'achat avec LocalStorage
- [ ] Page de détail produit
- [ ] Filtres et tri des produits
- [ ] Newsletter fonctionnelle

### Phase 3 - Backend
- [ ] API REST avec Express.js
- [ ] Base de données MongoDB
- [ ] Authentification JWT
- [ ] Panel administrateur

### Phase 4 - Production
- [ ] Tests unitaires
- [ ] Optimisation SEO
- [ ] Déploiement
- [ ] Monitoring et analytics

##  Contribution 🤝

Les contributions sont les bienvenues ! Pour contribuer :

1. Fork le projet
2. Créer une branche (`git checkout -b feature/AmazingFeature`)
3. Commit les changements (`git commit -m '[feat] Add AmazingFeature'`)
4. Push vers la branche (`git push origin feature/AmazingFeature`)
5. Ouvrir une Pull Request

## 📝 Licence

Ce projet est sous licence MIT. Voir le fichier `LICENSE` pour plus de détails.

## 👤 Auteur

**Merphy Madamba**
- GitHub: https://github.com/Merph-lng
- LinkedIn: https://www.linkedin.com/in/merph-dev?utm_source=share_via&utm_content=profile&utm_medium=member_android

##  Remerciements

- Inspiration design : [Dribbble](https://dribbble.com)
- Icônes : [Font Awesome](https://fontawesome.com)
- Images : [Unsplash](https://unsplash.com)

---

⭐ N'hésite pas à mettre une étoile si ce projet t'a aidé !
