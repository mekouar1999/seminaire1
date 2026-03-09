# 🎾 Application de Réservation de Terrains de Padel

## 📌 Description du projet

Cette application est une plateforme web permettant de **réserver des terrains de padel en ligne**.
Elle est développée avec la **stack MERN** :

* MongoDB
* Express.js
* React.js
* Node.js

L’objectif de cette application est de permettre aux joueurs de **réserver facilement un terrain**, tout en offrant aux clubs et aux administrateurs une interface simple pour **gérer les terrains et les réservations**.

La plateforme repose sur un système de **gestion des rôles** avec trois types d’utilisateurs :

* **Client (joueur)** : peut réserver un terrain
* **Admin (gestionnaire de terrain)** : gère ses terrains et ses réservations
* **Super Admin** : gère toute la plateforme

---

# 🚀 Fonctionnalités

## Joueur (Client)

Un joueur peut :

* créer un compte
* se connecter à la plateforme
* consulter les terrains disponibles
* voir les créneaux horaires disponibles
* réserver un terrain
* annuler une réservation
* consulter son historique de réservation

---

## Admin Terrain

Un administrateur représente un **club ou un terrain de padel**.

Il peut :

* gérer ses terrains
* définir les horaires disponibles
* consulter toutes les réservations de ses terrains
* modifier les informations d’un terrain
* bloquer certains créneaux (maintenance, événement, etc.)

Chaque administrateur peut uniquement gérer **ses propres terrains**.

---

## Super Admin

Le super administrateur possède un accès global à la plateforme.

Il peut :

* gérer tous les utilisateurs
* gérer tous les terrains
* consulter toutes les réservations
* superviser l’ensemble de la plateforme

---

# 🧱 Technologies utilisées

## Frontend

* React.js
* React Router
* Axios
* TailwindCSS ou Bootstrap

## Backend

* Node.js
* Express.js

## Base de données

* MongoDB

## Authentification

* JWT (JSON Web Token)
* Gestion des rôles utilisateurs

---

# ⚙️ Installation

## 1. Cloner le projet

git clone https://github.com/votre-repository/padel-booking.git
cd padel-booking

---

## 2. Installer les dépendances

### Backend

cd server
npm install

### Frontend

cd client
npm install

---

## 3. Configuration des variables d’environnement

Créer un fichier `.env` dans le dossier **server**.

Exemple :

PORT=5000
MONGO_URI=votre_uri_mongodb
JWT_SECRET=votre_secret_jwt

---

## 4. Lancer l’application

### Lancer le serveur backend

cd server
npm run dev

### Lancer le frontend

cd client
npm start

---

# 🌐 Accès à l'application

Frontend :

http://localhost:3000

Backend API :

http://localhost:5000

---

# 🎯 Objectif du projet

Ce projet vise à créer une **solution moderne de réservation de terrains de padel** permettant :

* de simplifier la gestion des réservations
* de digitaliser la gestion des clubs sportifs
* d’améliorer l’expérience utilisateur pour les joueurs
* de centraliser les réservations sur une seule plateforme

Ce projet peut servir comme :

* projet académique
* prototype de startup
* base pour une plateforme SaaS de réservation sportive

---

# 📈 Améliorations futures

Plusieurs fonctionnalités peuvent être ajoutées dans les versions futures :

* paiement en ligne
* notifications email
* notifications SMS
* application mobile
* système d’avis et de notation
* statistiques avancées pour les clubs

---

# 👨‍💻 Auteur

Projet développé avec la **stack MERN** pour créer une plateforme moderne de réservation de terrains de padel.
