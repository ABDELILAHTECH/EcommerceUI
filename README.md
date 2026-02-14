# EcommerceUI

EcommerceUI est un projet frontend complet simulant une boutique e-commerce.  
Il a été développé en **HTML, CSS et JavaScript pur (Vanilla JS)** sans aucun framework.  
Les données produits sont simulées via un fichier **JSON** et le panier est stocké dans le **LocalStorage** pour simuler un backend.

---

## 🔹 Fonctionnalités

- Affichage dynamique des produits depuis un fichier JSON
- Gestion du panier : ajout, suppression et calcul du total
- Persistance du panier entre sessions grâce au LocalStorage
- Interface responsive adaptée aux mobiles, tablettes et desktops
- Modularité du code : classes JS et modules pour cart, products et storage
- Media queries pour responsive design

---

## 🔹 Technologies utilisées

- HTML5
- CSS3 (avec media queries pour responsive design)
- JavaScript ES6 / Classes / Modules
- LocalStorage pour persistance du panier
- JSON pour simuler le backend

---

## 🔹 Structure du projet

EcommerceUI/
│
├── index.html # Page principale
├── css/
│ ├── style.css
│ ├── components.css
│ └── responsive.css
├── js/
│ ├── main.js
│ ├── ui.js
│ ├── cart.js
│ ├── products.js
│ └── storage.js
├── data/
│ └── products.json
├── images/ # Images produits