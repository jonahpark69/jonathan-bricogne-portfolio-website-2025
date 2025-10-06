# 👤 Portfolio — Site personnel

> Site vitrine dev/design : pages clés (Accueil/Projets/À propos/Contact/CV/Témoignages), bento‑grid, sidebar, et micro‑interactions.

---

## 📑 Sommaire

* [Aperçu](#-aperçu)
* [Pages & navigation](#-pages--navigation)
* [Fonctionnalités clés](#-fonctionnalités-clés)
* [Identité & UI](#-identité--ui)
* [Stack & prérequis](#-stack--prérequis)
* [Démarrage](#-démarrage)
* [Arborescence](#-arborescence)
* [Notes techniques](#-notes-techniques)
* [Accessibilité & SEO](#-accessibilité--seo)
* [Captures](#-captures)
* [Roadmap](#-roadmap)
* [Licence](#-licence)

---

## 👀 Aperçu

Portfolio personnel présentant mes projets (web/design), mon parcours et mes coordonnées. L’objectif est une **lecture rapide**, une **grille projets** claire et une mise en avant soignée de mon **profil**.

> **Statut** : `WIP`
> **Demo** : à renseigner

---

## 🧭 Pages & navigation

* **Accueil / Projets** : grille (bento) de mises en avant
* **À propos** : présentation, compétences, approche
* **CV** : expériences, compétences, liens téléchargeables
* **Témoignages** : retours clients/collègues
* **Contact** : formulaire simple + réseaux

---

## ✨ Fonctionnalités clés

* **Layout** : sidebar + zone contenu
* **Grille Projets** : CSS Grid, cartes lien → pages projet
* **Sections** : en‑têtes homogènes, hiérarchie H1→H3
* **Micro‑UI** : hover, focus, petites animations CSS
* **Composants** : header, hero, tuiles projet, modales légères (si besoin)

---

## 🖌️ Identité & UI

* **Typographies** : titres/texte selon charte (ex. *Inter* + titrage dédié)
* **Couleurs** : palette sobre (fond clair, texte sombre)
* **Icônes** : réseaux sociaux (SVG) + pictos UI
* **Visuels** : captures projets (optimisées)

---

## 🧱 Stack & prérequis

* **Front** : HTML5, CSS3, JavaScript (vanilla)
* **Outils** (optionnels) : VS Code + Live Server / `python3 -m http.server`

---

## 🚀 Démarrage

```bash
# Lancer un serveur local (au choix)
python3 -m http.server 5173
# ou
npx serve .
# puis http://localhost:5173
```

---

## 🌲 Arborescence

```
portfolio/
├─ assets/
│  ├─ css/style.css
│  ├─ js/main.js
│  └─ media/               # images, icônes, captures
├─ index.html               # Home / Projets
├─ about.html               # À propos
├─ contact.html             # Contact
├─ cv.html                  # CV
├─ testimonials.html        # Témoignages
└─ README.md
```

> Variante PHP possible : `index.php`, `project.php`, etc.

---

## 🛠️ Notes techniques

* **Grille bento** : classes `span-wX / span-hY` pour le maillage
* **CSS** : valeurs simples (px/rem) ; limiter `clamp()` si non souhaité
* **Performances** : images compressées (WebP si possible), lazy loading
* **JS** : interactions basiques (menu, modales, tabs)

---

## ♿ Accessibilité & SEO

* Semantique : `header/main/section/aside/footer`
* `alt` descriptifs, focus visibles, contraste suffisant
* Meta de base (`title`, `description`), structure H1→H2→H3

---

## 📸 Captures

*(à ajouter)*

* Home (grille projets)
* Page Projet (hero + détails)
* Page CV / Contact

---

## 🗺️ Roadmap

* [ ] Pages projet détaillées (1 par projet clé)
* [ ] Animations légères (entrées, hover tuiles)
* [ ] Optimisation Lighthouse
* [ ] Version EN (optionnel)

---

## 📜 Licence

Projet **privé** (usage personnel/portfolio).
