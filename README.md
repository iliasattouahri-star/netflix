# 🎬 Netflix Login Page Clone

Une reproduction moderne et élégante de la page de connexion Netflix, créée avec HTML, CSS et JavaScript vanilla.

![Netflix Login Preview](https://img.shields.io/badge/Netflix-E50914?style=for-the-badge&logo=netflix&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

---

## 📋 Table des matières

- [Aperçu](#-aperçu)
- [Fonctionnalités](#-fonctionnalités)
- [Installation](#-installation)
- [Structure du projet](#-structure-du-projet)
- [Technologies utilisées](#-technologies-utilisées)
- [Personnalisation](#-personnalisation)
- [Responsive Design](#-responsive-design)
- [Licence](#-licence)

---

## 🎯 Aperçu

Ce projet est une reproduction fidèle de la page de connexion Netflix avec des améliorations visuelles modernes incluant des animations, des effets de particules et un design glassmorphism.

---

## ✨ Fonctionnalités

### 🎨 Design & Animations
- ✅ Arrière-plan cinématique avec dégradés
- ✅ Particules rouges animées flottantes
- ✅ Effet glassmorphism sur le formulaire
- ✅ Animation d'apparition (fade up)
- ✅ Effet de brillance sur le bouton de connexion
- ✅ Transitions fluides sur tous les éléments

### 🔐 Formulaire
- ✅ Labels flottants animés
- ✅ Bouton afficher/masquer mot de passe
- ✅ Validation des champs (email & mot de passe)
- ✅ Animation de connexion (loading → succès)
- ✅ Checkbox personnalisée

### 🌐 Fonctionnalités supplémentaires
- ✅ Connexion sociale (Google & GitHub)
- ✅ Sélecteur de langue
- ✅ Section avantages Netflix
- ✅ Aperçu des appareils compatibles
- ✅ Footer complet avec liens

### 📱 Responsive
- ✅ Desktop (1200px+)
- ✅ Tablet (768px)
- ✅ Mobile (480px)

---

## 🚀 Installation

### Méthode 1 : Téléchargement direct

1. **Téléchargez** les fichiers du projet
2. **Placez-les** dans un même dossier
3. **Ouvrez** `index.html` dans votre navigateur

### Méthode 2 : Clone Git

```bash
# Cloner le repository
git clone https://github.com/votre-username/netflix-login-clone.git

# Accéder au dossier
cd netflix-login-clone

# Ouvrir dans le navigateur
open index.html
# ou
start index.html  # Windows
```

### Méthode 3 : Live Server (VSCode)

1. Installez l'extension **Live Server** dans VSCode
2. Clic droit sur `index.html`
3. Sélectionnez **"Open with Live Server"**

---

## 📁 Structure du projet

```
netflix-login-clone/
│
├── 📄 index.html      # Structure HTML principale
├── 🎨 style.css       # Styles et animations CSS
├── ⚡ script.js       # Logique JavaScript
└── 📖 README.md       # Documentation
```

### Description des fichiers

| Fichier | Description |
|---------|-------------|
| `index.html` | Structure sémantique HTML5 avec header, main et footer |
| `style.css` | 500+ lignes de CSS organisées par sections |
| `script.js` | Interactions : toggle password, validation, animations |
| `README.md` | Documentation complète du projet |

---

## 🛠 Technologies utilisées

| Technologie | Utilisation |
|-------------|-------------|
| **HTML5** | Structure sémantique |
| **CSS3** | Styles, animations, responsive |
| **JavaScript ES6** | Interactions et validations |
| **CSS Grid** | Layout du footer |
| **Flexbox** | Alignements et dispositions |
| **CSS Animations** | Particules, transitions |
| **CSS Variables** | Couleurs principales |

---

## 🎨 Personnalisation

### Modifier les couleurs

Dans `style.css`, les couleurs principales sont :

```css
/* Couleur principale Netflix */
#e50914  /* Rouge Netflix */
#b81d24  /* Rouge foncé */

/* Arrière-plan */
#000     /* Noir */
#141414  /* Gris très foncé */
#333     /* Gris input */
#404040  /* Gris input focus */

/* Texte */
#fff     /* Blanc */
#b3b3b3  /* Gris clair */
#737373  /* Gris moyen */
#8c8c8c  /* Gris labels */
```

### Modifier les animations

```css
/* Durée des particules */
.particle {
  animation: rise 15s infinite; /* Changer 15s */
}

/* Animation du formulaire */
.login-box {
  animation: fadeUp 0.6s ease; /* Changer 0.6s */
}

/* Effet brillance bouton */
.btn-primary::after {
  transition: transform 0.6s ease; /* Changer 0.6s */
}
```

### Ajouter plus de particules

Dans `index.html`, ajoutez plus de `<div class="particle"></div>` et dans `style.css` :

```css
.particle:nth-child(11) { left: 8%; animation-delay: -5s; }
.particle:nth-child(12) { left: 92%; animation-delay: -9s; }
/* ... */
```

---

## 📱 Responsive Design

### Breakpoints

| Écran | Largeur | Adaptations |
|-------|---------|-------------|
| Desktop | > 768px | Layout complet |
| Tablet | ≤ 768px | Padding réduit, footer 2 colonnes |
| Mobile | ≤ 480px | Boutons sociaux en colonne, footer simplifié |

### Test responsive

```css
/* Dans le navigateur, appuyez sur F12 puis Ctrl+Shift+M */
/* Ou utilisez les DevTools > Toggle device toolbar */
```

---

## 🔧 Fonctions JavaScript

### togglePwd()
Affiche ou masque le mot de passe.

### Form Submit Handler
Simule une connexion avec animation de loading et succès.

### Input Validation
Valide l'email (regex) et le mot de passe (min 6 caractères).

### Language Selector
Change la langue au clic (FR → EN → ES → DE).

---

## 📝 À faire (TODO)

- [ ] Ajouter une page d'inscription
- [ ] Implémenter OAuth réel (Google/GitHub)
- [ ] Ajouter le mode sombre/clair
- [ ] Créer une page de récupération de mot de passe
- [ ] Ajouter des tests unitaires
- [ ] Optimiser les performances (lazy loading)

---

## ⚠️ Avertissement

Ce projet est à **but éducatif uniquement**. Netflix® est une marque déposée de Netflix, Inc. Ce projet n'est pas affilié à Netflix.

---

## 📄 Licence

```
MIT License

Copyright (c) 2024

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
```

---

## 🤝 Contribution

Les contributions sont les bienvenues !

1. **Fork** le projet
2. Créez votre branche (`git checkout -b feature/AmazingFeature`)
3. **Commit** vos changements (`git commit -m 'Add AmazingFeature'`)
4. **Push** vers la branche (`git push origin feature/AmazingFeature`)
5. Ouvrez une **Pull Request**

---

## 📧 Contact

Pour toute question ou suggestion, n'hésitez pas à ouvrir une **issue** sur GitHub.

---

<p align="center">
  Fait avec ❤️ et beaucoup de ☕
</p>

<p align="center">
  ⭐ N'oubliez pas de star le repo si vous l'aimez !
</p>
