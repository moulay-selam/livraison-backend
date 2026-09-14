# 🌐 WASALI Web

### Plateforme intelligente de livraison collaborative nationale et internationale

WASALI Web est l'application web de la plateforme **WASALI**, développée dans le cadre d'un **Projet de Fin d'Études (PFE)**.

La plateforme permet de connecter les **expéditeurs**, les **voyageurs** et les **administrateurs** afin de faciliter la livraison collaborative de colis à l'échelle nationale et internationale.

---

# 📖 À propos

WASALI est une plateforme intelligente de livraison collaborative permettant aux voyageurs de transporter des colis pour des expéditeurs lors de leurs déplacements entre différentes villes ou pays.

Le système comprend :

- 🌐 Application Web (React)
- 📱 Application Mobile (React Native)
- ⚙️ API Backend (Spring Boot)
- 🗄️ Base de données PostgreSQL

---

# 🚀 Fonctionnalités

## 👤 Authentification

- Inscription et connexion sécurisées
- Authentification JWT
- Gestion du profil utilisateur
- Gestion des rôles

## 📦 Gestion des colis

- Création et publication des colis
- Consultation des colis disponibles
- Suivi des livraisons
- Historique des colis

## ✈️ Gestion des trajets

- Publication des trajets
- Consultation des trajets disponibles
- Acceptation ou refus des demandes
- Gestion des disponibilités des voyageurs

## 📍 Suivi en temps réel

- Géolocalisation GPS
- Suivi des livraisons
- Notifications en temps réel

## 🔐 Sécurité

- JWT Authentication
- Protection des routes
- Validation des données
- Contrôle des accès

## 📊 Tableau de bord

- Gestion des utilisateurs
- Gestion des colis
- Gestion des trajets
- Statistiques générales

---

# 🛠️ Technologies utilisées

## Frontend

- React
- Vite
- JavaScript / TypeScript
- React Router
- Axios
- Context API
- Tailwind CSS

## Backend

- Spring Boot
- Spring Security
- JWT Authentication
- REST API

## Base de données

- PostgreSQL

---

# 📁 Structure du projet

## Frontend

```text
frontend/
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   ├── context/
│   ├── hooks/
│   ├── layouts/
│   ├── pages/
│   ├── routes/
│   ├── services/
│   └── App.jsx
├── package.json
├── vite.config.js
└── README.md
```

## Backend

```text
livraison-backend/
├── .mvn/
├── logs/
├── uploads/
├── src/
│   ├── main/
│   │   ├── java/com/livraison/backend/
│   │   │   ├── auth/
│   │   │   ├── config/
│   │   │   ├── controller/
│   │   │   ├── dto/
│   │   │   ├── entity/
│   │   │   ├── exception/
│   │   │   ├── repository/
│   │   │   ├── security/
│   │   │   ├── service/
│   │   │   └── LivraisonBackendApplication.java
│   │   └── resources/
│   └── test/java/com/livraison/backend/
├── pom.xml
├── mvnw
└── README.md
```

---

# ⚙️ Installation

## Cloner le projet

```bash
git clone https://github.com/Mouaye4849/livraison-project.git
```

## Frontend

```bash
cd frontend
npm install
npm run dev
```

### Build de production

```bash
npm run build
```

### Prévisualiser le build

```bash
npm run preview
```

## Backend

```bash
cd livraison-backend
mvn spring-boot:run
```

Ou :

```bash
./mvnw spring-boot:run
```

---

# 🔗 Backend Spring Boot

Le frontend communique avec une API REST développée avec Spring Boot.

## Fonctionnalités du Backend

- Authentification JWT
- Gestion des colis
- Gestion des trajets
- Notifications
- Vérification OTP
- Suivi GPS en temps réel
- API REST sécurisée

---

# 🏗️ Architecture

```text
React Frontend
       │
       ▼
     REST API
       │
       ▼
Spring Boot Backend
       │
       ▼
   PostgreSQL
```

---

# 👨‍💻 Auteur

**Moulaye Elhacen Selam**

Licence en Informatique (MIAGE)  
Faculté des Sciences et Techniques  
Université de Nouakchott Al Aasriya

---

# 🎓 Projet de Fin d'Études

## WASALI

Conception et développement d'un système de livraison nationale et internationale de colis par les voyageurs.

## Technologies du projet

- Spring Boot
- React
- React Native
- PostgreSQL
- JWT Authentication
- GPS Tracking
- OTP Verification

## Année universitaire

**2025 – 2026**
