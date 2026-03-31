Title: TP majeurs
Save_as: pages/tp-majeurs.html

# Présentation des travaux pratiques majeurs :

---

## 🎓 Première année de BTS SIO

---

## ✅ TP 1 – Gestion d'une base de données de pays

> **FICHE DESCRIPTIVE :**
>
> - **Sujet :** Gestion d'une base de données de pays
> - **Langages :** PHP (PDO), HTML/CSS
> - **Base de données :** MySQL (tables `Country`, `City`)
>
> **Objectif :** Manipuler et afficher des données issues d'une base relationnelle via des pages PHP dynamiques.

### 📋 Présentation

Ce TP consiste à créer une application web en PHP permettant de récupérer et afficher des données géographiques depuis une base MySQL. L'utilisateur peut naviguer entre les continents, consulter les pays et leurs informations (population, superficie, drapeau, capitale), et mettre à jour certaines données via un formulaire.

### 🛠️ Fonctionnalités principales

- Affichage de la liste des **continents** et des **pays** associés
- Détail d'un pays : drapeau, population, superficie, capitale
- **Formulaire de mise à jour** : modification de la population et de l'espérance de vie via une requête SQL `UPDATE`

### 💡 Compétences mobilisées 

- Développement web dynamique en **PHP avec PDO**
- Requêtes **SQL** (SELECT, UPDATE)
- Manipulation de **paramètres GET** dans les URL
- Organisation du code en fichiers séparés (`db.php`, `index2.php`, `DetailsPays.php`)

---

## ✅ TP 2 – Recherche de films & acteurs avec l'API TMDb

> **FICHE DESCRIPTIVE :**
>
> - **Sujet :** Utilisation d'une API externe (The Movie Database)
> - **Langages :** PHP, HTML/CSS
> - **Outil externe :** TMDb API
>
> **Objectif :** Créer une application de recherche interactive de films et d'acteurs via des formulaires HTML et une API REST.

### 📋 Présentation

Ce TP combine formulaires HTML et appel à une API externe pour réaliser une recherche interactive. L'utilisateur peut rechercher un film ou un acteur, et l'application affiche les résultats (affiches, photos de profil) en interrogeant l'API TMDb en temps réel.

### 🛠️ Fonctionnalités principales

- Formulaire de recherche de **films** (`movie.php`)
- Formulaire de recherche d'**acteurs** (`name.php`)
- Affichage des résultats : affiches, noms, informations

### 💡 Compétences mobilisées

- Consommation d'une **API REST** en PHP
- Utilisation des méthodes **GET / POST** dans les formulaires HTML
- Traitement des données JSON retournées par l'API

---

## 🎓 Deuxième année de BTS SIO

---

## ✅ TP 3 – SavonApi : application de gestion de recettes de savons

> **FICHE DESCRIPTIVE :**
>
> - **Sujet :** Consommation d'une API REST fournie par le professeur
> - **Langages :** TypeScript, HTML, CSS
> - **Framework :** Angular
> - **Lien GitHub :** [AkramanSou/SavonApi](https://github.com/AkramanSou/SavonApi)
>
> **Objectif :** Développer une application web Angular permettant de gérer des recettes de savons via une API REST.

### 📋 Présentation

Dans ce projet, une API REST a été fournie par le professeur. L'objectif était de créer une application Angular capable de communiquer avec cette API pour créer, afficher et enregistrer des recettes de savons. C'est ma première expérience avec le framework Angular et le développement frontend en TypeScript.

### 🛠️ Fonctionnalités principales

- **Affichage** de la liste des recettes disponibles
- **Création** d'une nouvelle recette via un formulaire
- **Enregistrement** des recettes en communiquant avec l'API REST
- Navigation entre les différentes vues grâce au **routing Angular**

### 💡 Compétences mobilisées

- Développement frontend avec **Angular** (composants, services, routing)
- Langage **TypeScript**
- Consommation d'une **API REST** (requêtes HTTP GET/POST)
- Gestion de l'état de l'application avec des **services Angular**

---

## ✅ TP 4 – eCommerce2 : site de vente d'équipements de boxe

> **FICHE DESCRIPTIVE :**
>
> - **Sujet :** Création d'un site e-commerce
> - **Langages :** HTML, CSS, JavaScript, Kotlin
> - **Lien GitHub :** [AkramanSou/eCommerce2](https://github.com/AkramanSou/eCommerce2)
>
> **Objectif :** Concevoir et développer un site e-commerce de vente d'équipements de boxe avec un catalogue produits et une interface utilisateur soignée.

### 📋 Présentation

Ce projet consiste en la réalisation d'un site e-commerce dédié à la vente d'équipements de boxe (gants, protège-dents, sacs de frappe...). L'accent a été mis sur la qualité de l'interface utilisateur et la présentation des produits. C'est un projet qui m'a particulièrement motivé car il combine ma passion pour le sport et le développement web.

### 🛠️ Fonctionnalités principales

- **Catalogue produits** avec présentation des équipements de boxe
- **Interface responsive** adaptée mobile et desktop
- Navigation fluide entre les catégories de produits
- Design soigné et cohérent avec l'univers de la boxe

### 💡 Compétences mobilisées

- Développement web **HTML / CSS / JavaScript**
- Intégration de logique backend avec **Kotlin**
- Conception d'une **interface utilisateur** orientée e-commerce
- Gestion de projet et versioning avec **Git / GitHub**