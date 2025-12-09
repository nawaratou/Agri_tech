# Exercice : Page Web Agritech App

## Objectif
Créer une page web responsive pour une application fictive **Agritech App** en utilisant **HTML**, **CSS** et **Bootstrap 5**, incluant :  
- Une topbar avec informations de contact et réseaux sociaux  
- Un menu de navigation responsive (desktop et mobile)  
- Une section hero avec boutons d'action  
- Une galerie de cartes présentant des indicateurs FAO, la météo et les formations  
- Des sections supplémentaires pour les formations, les équipes et les statistiques  
- Un footer complet avec newsletter, liens utiles et contact  

---
## Technologies utilisées
- HTML5
- CSS3 (`index.css`)
- Bootstrap 5.3.2
- Font Awesome 6.5
- Bootstrap Icons 1.11.1

---
## Structure du projet
# Sections principales
------
### 1. Topbar (desktop)
- Affiche email et téléphone
- Logo et nom de l’application
- Drapeau du Niger et icônes réseaux sociaux
-----
### 2. Menu de navigation
- Responsive : menu mobile via checkbox et overlay
- Liens : Home, Formations, Météo, Indicateurs
- Bouton **Connect** visible sur mobile et desktop
----
### 3. Hero Section
- Titre principal et description
- Boutons d’action : "Discutons" et "Nos services"
- Version flottante pour mobile/tablette
----
### 4. Galerie (Cards)
- 3 cartes principales : Indicateurs FAO, Météo locale, Formation pratique
- Overlay avec icônes, titre, texte et lien
- Version mobile/tablette avec cartes textuelles
-----
### 5. Sections additionnelles
- Statistiques : clients satisfaits et agriculteurs formés
- Cards météo et FAO
- Formations récentes
- Équipe avec photos et spécialités
---
### 6. Footer
- Newsletter avec input et bouton
- À propos, liens utiles, services et contact
- Bas de page avec copyright

---

## Particularités
- Utilisation de classes Bootstrap pour le responsive (`d-md-none`, `d-md-flex`, `col-12`, `col-md-4`, etc.)
- Boutons personnalisés avec classes `btn-green-custom` et `btn-yellow`
- Galerie et cartes avec effets overlay
- Icônes intégrées via Font Awesome et Bootstrap Icons
- Menu mobile contrôlé par une checkbox pour l’ouverture/fermeture

---

## Points d'amélioration possibles
- Ajouter un slider dynamique pour la section Hero
- Intégrer les données météo et FAO en temps réel via API
- Ajouter animations et transitions CSS pour les overlays et boutons
- Optimiser le SEO et l’accessibilité (balises alt, aria-label, etc.)
