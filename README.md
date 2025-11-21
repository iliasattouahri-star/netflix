# 🎬 Netflix Login Page Clone

Une reproduction moderne et élégante de la page de connexion Netflix, créée uniquement avec **HTML** et **CSS**.

![Netflix Login Preview](https://img.shields.io/badge/Netflix-E50914?style=for-the-badge&logo=netflix&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

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

Ce projet est une reproduction fidèle de la page de connexion Netflix avec des améliorations visuelles modernes. Entièrement réalisé en HTML et CSS pur, sans JavaScript.

---

## ✨ Fonctionnalités

### 🎨 Design & Animations (CSS uniquement)
- ✅ Arrière-plan cinématique avec dégradés
- ✅ Particules rouges animées flottantes
- ✅ Effet glassmorphism sur le formulaire
- ✅ Animation d'apparition (fade up)
- ✅ Effet de brillance sur le bouton hover
- ✅ Transitions fluides sur tous les éléments
- ✅ Labels flottants animés (CSS only)

### 🔐 Formulaire
- ✅ Labels flottants avec `:placeholder-shown`
- ✅ Checkbox personnalisée
- ✅ Validation HTML5 native
- ✅ États focus stylisés

### 🌐 Éléments inclus
- ✅ Boutons connexion sociale (Google & GitHub)
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
```

### Méthode 3 : Live Server (VSCode)

1. Installez l'extension **Live Server**
2. Clic droit sur `index.html`
3. Sélectionnez **"Open with Live Server"**

---

## 📁 Structure du projet

```
netflix-login-clone/
│
├── 📄 index.html      # Structure HTML
├── 🎨 style.css       # Styles et animations
└── 📖 README.md       # Documentation
```

| Fichier | Description |
|---------|-------------|
| `index.html` | Structure sémantique HTML5 |
| `style.css` | 500+ lignes CSS avec animations |
| `README.md` | Documentation du projet |

---

## 🛠 Technologies utilisées

| Technologie | Utilisation |
|-------------|-------------|
| **HTML5** | Structure sémantique |
| **CSS3** | Styles, animations, responsive |
| **CSS Grid** | Layout du footer |
| **Flexbox** | Alignements |
| **CSS Animations** | @keyframes pour particules |
| **CSS Pseudo-classes** | :hover, :focus, :checked |
| **CSS Pseudo-elements** | ::before, ::after |

---

## 🎨 Personnalisation

### Couleurs principales

```css
/* Rouge Netflix */
#e50914
#b81d24

/* Arrière-plan */
#000
#141414
#333

/* Texte */
#fff
#b3b3b3
#737373
```

### Modifier les animations

```css
/* Particules - durée */
.particle {
  animation: rise 15s infinite;
}

/* Formulaire - apparition */
.login-box {
  animation: fadeUp 0.6s ease;
}

/* Bouton - effet brillance */
.btn-primary::after {
  transition: transform 0.6s ease;
}
```

### Ajouter des particules

Dans `index.html` :
```html
<div class="particle"></div>
```

Dans `style.css` :
```css
.particle:nth-child(11) { left: 8%; animation-delay: -5s; }
```

---

## 📱 Responsive Design

| Écran | Largeur | Adaptations |
|-------|---------|-------------|
| Desktop | > 768px | Layout complet |
| Tablet | ≤ 768px | Padding réduit |
| Mobile | ≤ 480px | Colonne unique |

---

## 🎯 Techniques CSS utilisées

### Labels flottants (sans JS)

```css
.input-group input:focus + label,
.input-group input:not(:placeholder-shown) + label {
  top: 10px;
  font-size: 11px;
  color: #e50914;
}
```

### Checkbox personnalisée

```css
.checkbox-wrap input:checked + .checkmark {
  background: #e50914;
}

.checkbox-wrap input:checked + .checkmark::after {
  content: '✓';
}
```

### Effet brillance bouton

```css
.btn-primary::after {
  background: linear-gradient(90deg, transparent, rgba(255,255,255,0.3), transparent);
  transform: translateX(-100%);
}

.btn-primary:hover::after {
  transform: translateX(100%);
}
```

---

## ⚠️ Avertissement

Ce projet est à **but éducatif uniquement**. Netflix® est une marque déposée de Netflix, Inc.

---

## 📄 Licence

```
MIT License
Copyright (c) 2024
```

---

## 🤝 Contribution

1. **Fork** le projet
2. Créez votre branche (`git checkout -b feature/NewFeature`)
3. **Commit** (`git commit -m 'Add NewFeature'`)
4. **Push** (`git push origin feature/NewFeature`)
5. Ouvrez une **Pull Request**

---

<p align="center">
  Fait avec ❤️ en HTML & CSS
</p>

<p align="center">
  ⭐ Star le repo si tu aimes !
</p>
