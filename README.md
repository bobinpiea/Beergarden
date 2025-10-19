# Beergarden# 🍺 Beergarden

Site vitrine one-page pour un pub/bar à bières développé lors de mon apprentissage du développement web.

## 📋 À propos

Projet de site web statique créé en apprenant le HTML et CSS, notamment via les ressources OpenClassrooms. Le site présente un pub fictif avec son atmosphère, ses traditions et ses services.

## ✨ Fonctionnalités

- Navigation fixe avec liens de menu et réseaux sociaux
- Section "Beer Tradition" et "Pub Story"
- Galerie photos avec effet hover et animation de rotation
- Section services avec 4 prestations
- Effet parallax sur les sections avec image de fond
- Intégration Google Maps
- Design responsive (mobile, tablette, desktop)

## 🛠️ Technologies utilisées

- **HTML5** - Structure de la page
- **CSS3** - Styles et animations
  - Flexbox et Grid
  - Animations CSS (rotation)
  - Effet parallax (background-attachment: fixed)
  - Media queries pour le responsive
- **Font Awesome** - Icônes réseaux sociaux
- **Google Fonts** - Polices Oswald et Raleway

## 📂 Structure

```
Beergarden/
├── index.html
├── style.css
└── images/
    ├── header/
    └── main/
```

## 🚀 Installation

```bash
# Cloner le projet
git clone https://github.com/bobinpiea/Beergarden.git

# Ouvrir le fichier
cd Beergarden
# Ouvrir index.html dans votre navigateur
```

## 🎨 Palette de couleurs

- Couleur principale : `#c18d39` (doré)
- Overlay galerie : `rgba(193, 141, 57, 0.9)`
- Fond navigation : `rgba(0, 0, 0, 0.6)`

## 📱 Responsive

Le site s'adapte automatiquement aux différentes tailles d'écran :
- Desktop : galerie en 4 colonnes, sections côte à côte
- Mobile : navigation verticale, galerie en colonne unique, sections empilées