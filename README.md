<h1 align="center">
LogiStock
</h1>

<p align="center">
B2B Stock and Logistics Management Platform
</p>

<br>

<p align="center">
  <img src="https://img.shields.io/badge/React-Frontend-blue" />
  <img src="https://img.shields.io/badge/SpringBoot-Backend-green" />
  <img src="https://img.shields.io/badge/MySQL-Database-orange" />
  <img src="https://img.shields.io/badge/JWT-Authentication-red" />
</p>

---
## 🌍 Navigation

- 🇬🇧 [English Version](#english)
- 🇫🇷 [Version Française](#francais)


---

<a id="english"></a>

# 🇬🇧 English Version

<p align="center">
  <img src="https://drive.google.com/uc?id=1EvzkKywXmq366k6nRjM9hSKySdmh6ko9" width="250" alt="LogiStock Logo"/>
</p>

## 📦 About the Project

LogiStock is a B2B inventory and logistics management platform developed as a Final Year Project (PFE).

The platform aims to digitalize and optimize supply chain management by connecting clients, suppliers, managers, and administrators through a centralized and secure system.

LogiStock provides a complete environment for managing products, inventories, orders, contracts, invoices, logistics operations, and user interactions.

### Main Features

- Inventory Management
- Product Catalog Management
- Order Processing
- Supplier Management
- Client Management
- Contract Management
- Invoice Generation
- Digital Signature Integration
- Shipment Tracking
- Authentication & Authorization
- Activity Monitoring

---

## 🎯 Objectives

The primary objective of LogiStock is to improve efficiency and transparency in inventory and logistics operations.

The platform helps organizations:

- Reduce manual processes
- Improve communication between stakeholders
- Centralize business operations
- Enhance order tracking
- Automate invoice generation
- Secure access through role-based permissions
- Optimize stock management

---

## 👥 System Actors

### 🛒 Client

The client is responsible for purchasing products and tracking orders.

Features:

- Browse product catalog
- Search and filter products
- Place orders
- Track order status
- View invoices
- Manage personal profile

---

### 🧑‍💼 Supplier

The supplier provides products and manages deliveries.

Features:

- Manage products
- Update stock quantities
- Receive customer orders
- Manage deliveries
- Generate invoices
- Track order fulfillment

---

### 📊 Manager

The manager supervises logistics and inventory operations.

Features:

- Monitor inventory levels
- Validate business operations
- Supervise logistics activities
- Manage workflows
- Track performance indicators

---

### ⚙️ Administrator

The administrator manages the entire platform.

Features:

- Manage users
- Assign roles and permissions
- Configure system settings
- Monitor activities
- Ensure platform security

---

## 🛠️ Technologies Used

### Frontend

- React
- TypeScript
- Tailwind CSS
- Axios
- React Router

### Backend

- Spring Boot
- Spring Security
- JWT Authentication
- Hibernate
- JPA

### Database

- MySQL

### Development Tools

- Git
- GitHub
- Postman
- IntelliJ IDEA
- VS Code
- Maven

---

## 🔐 Authentication & Access Management
![Login](https://drive.google.com/uc?id=1hOVz9orLu8gSlNmqUKDBgLLJ54mjZAfC)  
![Registration](https://drive.google.com/uc?id=1BbJZkM4D1Aro07IqIJ3iHG2qrx51JKOJ)  
![Roles and Signature](https://drive.google.com/uc?id=1dfzBYG0_ps58sKiVbNJBpwT-uAo3wup9)  
![Invoice](https://drive.google.com/uc?id=1CGyw3PlpEXoKJbc2-T72tmWyo25KBF5C)  

---

## 👤 User Interfaces & Demonstrations
### 🧑‍💼 Supplier Interface
![Supplier Interface](https://drive.google.com/uc?id=1IrgT23THbtqrrbSx-QYeFSq13sYOlk8A)  
**Demo Video:** [Supplier Workflow](https://drive.google.com/file/d/1z-taglKqUk3bOl7pUZqCvxwtLqNhj-7z/view?usp=sharing)

### 📊 Manager Interface
![Manager Interface](https://drive.google.com/uc?id=1pHruU34ZxZdzmxznhhlUnJIydx50mMsf)  
**Demo Video:** [Manager Workflow](https://drive.google.com/file/d/1flbgS3rr_yNCE6e46GnTgkijznsf3Ckx/view?usp=drive_link)

### 🛒 Client Interface
![Client Interface](https://drive.google.com/uc?id=1DUafhG6lbqTeT6inhlVUaaFfDm_lnUOW)  
**Demo Video:** [Client Workflow](https://drive.google.com/file/d/1ywNUr1047s2mG4d2Cy64gkyt3HnNV_Mt/view?usp=drive_link)

### ⚙️ Administrator Interface
![Administrator Interface](https://drive.google.com/uc?id=15OAAW0OMGIJ2F1PBBJF76xH8TEEYCmQ-)  
**Demo Video:** [Administrator Workflow](https://drive.google.com/file/d/1XpTn4Xpwu1JyY_jSefTJ2hSV8s127TFV/view?usp=drive_link)

---
## 🏗️ Project Architecture

LogiStock follows a layered architecture based on a modern web application structure.

The system is divided into three main layers:

- Presentation Layer: Handles user interaction through the React interface.
- Business Layer: Contains the application logic and business rules.
- Data Access Layer: Manages communication with the database.

```text
                User Interface
                     │
                     ▼
             Frontend (React)
                     │
                     ▼
              REST API Layer
                     │
                     ▼
          Backend (Spring Boot)
                     │
                     ▼
           Business Logic Layer
                     │
                     ▼
             Data Access Layer
                     │
                     ▼
              MySQL Database
```

---

## 📁 Project Structure

```text
LogiStock/
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   ├── hooks/
│   │   └── routes/
│   │
│   └── package.json
│
├── backend/
│   ├── src/
│   │   ├── controller/
│   │   ├── service/
│   │   ├── repository/
│   │   ├── entity/
│   │   ├── security/
│   │   └── config/
│   │
│   └── pom.xml
│
├── database/
│
├── docs/
│
└── README.md
```

---

# 🚀 Installation & Setup

Follow these steps to run the project locally.

---

## 1. Clone Repository

```bash
git clone https://github.com/LogiStock-Team/LogiStock_PFE_2026.git
```

Navigate to the project directory:

```bash
cd LogiStock_PFE_2026
```

---

# Backend Setup

Go to the backend folder:

```bash
cd backend
```

Install dependencies:

```bash
mvn clean install
```

Run the Spring Boot application:

```bash
mvn spring-boot:run
```

Backend server:

```text
http://localhost:8080
```

---

# Frontend Setup

Open another terminal:

```bash
cd frontend
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Frontend server:

```text
http://localhost:5173
```

---

# ⚙️ Database Configuration

The project uses MySQL.

Required configuration:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/logistock
spring.datasource.username=root
spring.datasource.password=your_password
```

Before running the application:

- Create the database
- Configure database credentials
- Start MySQL server

---

# 🔒 Security

LogiStock implements several security mechanisms:

## Authentication

- JWT-based authentication
- Secure login system
- Protected API endpoints

## Authorization

- Role-Based Access Control (RBAC)
- Permission management
- Restricted access according to user roles

## Data Protection

- Password encryption
- Secure communication between layers
- Validation of user requests

---

# 📈 Future Improvements

Possible improvements for future versions:

- 📱 Mobile application
- 🔔 Real-time notifications
- 📊 Advanced analytics dashboard
- 🤖 AI-based stock demand prediction
- 🏢 Multi-warehouse management
- 📍 Real-time delivery tracking
- ☁️ Cloud deployment
- 🔄 Automated backups
---
# 👨‍💻 Development Team
## Final Year Project (PFE)
Developed by:

- Safaa Mounkid
- Marwa Maqsoudi
- Meryem Mazzi

---
# 📜 License 

This project was developed for academic purposes as part of a Final Year Project (PFE).

All rights reserved © 2026.

---

<br>

<a id="francais"></a>

# 🇫🇷 Version Française

<p align="center">
<img src="https://drive.google.com/uc?id=1EvzkKywXmq366k6nRjM9hSKySdmh6ko9" width="250" alt="Logo LogiStock"/>
</p>

## 📦 À propos du projet

LogiStock est une plateforme B2B de gestion de stock et de logistique développée dans le cadre d'un Projet de Fin d'Études (PFE).

La plateforme vise à digitaliser et optimiser la chaîne logistique en connectant les clients, fournisseurs, gestionnaires et administrateurs à travers un système centralisé et sécurisé.

LogiStock offre un environnement complet permettant de gérer les produits, les stocks, les commandes, les contrats, les factures, les opérations logistiques et les interactions entre les différents acteurs.

### Fonctionnalités principales

- Gestion des stocks
- Gestion du catalogue de produits
- Traitement des commandes
- Gestion des fournisseurs
- Gestion des clients
- Gestion des contrats
- Génération des factures
- Intégration de la signature électronique
- Suivi des livraisons
- Authentification et autorisation
- Suivi des activités

---

## 🎯 Objectifs

L'objectif principal de LogiStock est d'améliorer l'efficacité et la transparence des opérations de gestion de stock et de logistique.

La plateforme permet de :

- Réduire les tâches manuelles
- Améliorer la communication entre les acteurs
- Centraliser les opérations métier
- Faciliter le suivi des commandes
- Automatiser la génération des factures
- Sécuriser l'accès aux fonctionnalités
- Optimiser la gestion des stocks

---

## 👥 Acteurs du système

### 🛒 Client

Le client est responsable de l'achat des produits et du suivi de ses commandes.

Fonctionnalités :

- Consulter le catalogue de produits
- Rechercher et filtrer les produits
- Passer des commandes
- Suivre l'état des commandes
- Consulter les factures
- Gérer son profil

---

### 🧑‍💼 Fournisseur

Le fournisseur assure la mise à disposition des produits et la gestion des livraisons.

Fonctionnalités :

- Gérer les produits
- Mettre à jour les quantités en stock
- Recevoir les commandes
- Gérer les livraisons
- Générer les factures
- Assurer le suivi des commandes

---

### 📊 Gestionnaire

Le gestionnaire supervise les opérations logistiques et la gestion des stocks.

Fonctionnalités :

- Surveiller les niveaux de stock
- Valider les opérations
- Superviser les activités logistiques
- Gérer les flux de travail
- Suivre les indicateurs de performance

---

### ⚙️ Administrateur

L'administrateur gère l'ensemble de la plateforme.

Fonctionnalités :

- Gérer les utilisateurs
- Attribuer les rôles et permissions
- Configurer le système
- Superviser les activités
- Garantir la sécurité de la plateforme

---

## 🛠️ Technologies utilisées

### Frontend

- React
- TypeScript
- Tailwind CSS
- Axios
- React Router

### Backend

- Spring Boot
- Spring Security
- JWT Authentication
- Hibernate
- JPA

### Base de données

- MySQL

### Outils de développement

- Git
- GitHub
- Postman
- IntelliJ IDEA
- VS Code
- Maven

---
## 🔐 Authentification et Gestion des Accès
![Connexion](https://drive.google.com/uc?id=1hOVz9orLu8gSlNmqUKDBgLLJ54mjZAfC)  
![Inscription](https://drive.google.com/uc?id=1BbJZkM4D1Aro07IqIJ3iHG2qrx51JKOJ)  
![Gestion des rôles](https://drive.google.com/uc?id=1dfzBYG0_ps58sKiVbNJBpwT-uAo3wup9)  
![Facture](https://drive.google.com/uc?id=1CGyw3PlpEXoKJbc2-T72tmWyo25KBF5C)  

---

## 👤 Interfaces utilisateurs et démonstrations
### 🧑‍💼 Interface Fournisseur
![Interface Fournisseur](https://drive.google.com/uc?id=1IrgT23THbtqrrbSx-QYeFSq13sYOlk8A)  
**Vidéo Démo :** [Vue Fournisseur](https://drive.google.com/file/d/1z-taglKqUk3bOl7pUZqCvxwtLqNhj-7z/view?usp=sharing)

### 📊 Interface Gestionnaire
![Interface Gestionnaire](https://drive.google.com/uc?id=1pHruU34ZxZdzmxznhhlUnJIydx50mMsf)  
**Vidéo Démo :** [Vue Gestionnaire](https://drive.google.com/file/d/1flbgS3rr_yNCE6e46GnTgkijznsf3Ckx/view?usp=drive_link)

### 🛒 Interface Client
![Interface Client](https://drive.google.com/uc?id=1DUafhG6lbqTeT6inhlVUaaFfDm_lnUOW)  
**Vidéo Démo :** [Vue Client](https://drive.google.com/file/d/1ywNUr1047s2mG4d2Cy64gkyt3HnNV_Mt/view?usp=drive_link)

### ⚙️ Interface Administrateur
![Interface Administrateur](https://drive.google.com/uc?id=15OAAW0OMGIJ2F1PBBJF76xH8TEEYCmQ-)  
**Vidéo Démo :** [Vue Administrateur](https://drive.google.com/file/d/1XpTn4Xpwu1JyY_jSefTJ2hSV8s127TFV/view?usp=drive_link)

---

## 🏗️ Architecture du projet

LogiStock adopte une architecture en couches basée sur une structure moderne d’application web.

Le système est composé principalement de trois couches :

- Couche Présentation : Gestion de l’interaction utilisateur avec React.
- Couche Métier : Contient la logique applicative et les règles métier.
- Couche Accès aux données : Assure la communication avec la base de données.

```text
                Interface Utilisateur
                       │
                       ▼
                Frontend (React)
                       │
                       ▼
                 Couche API REST
                       │
                       ▼
              Backend (Spring Boot)
                       │
                       ▼
                Couche Métier
                       │
                       ▼
             Couche Accès aux données
                       │
                       ▼
              Base MySQL
```

---

# 📁 Structure du projet

```text
LogiStock/
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   ├── hooks/
│   │   └── routes/
│   │
│   └── package.json
│
├── backend/
│   ├── src/
│   │   ├── controller/
│   │   ├── service/
│   │   ├── repository/
│   │   ├── entity/
│   │   ├── security/
│   │   └── config/
│   │
│   └── pom.xml
│
├── database/
│
├── docs/
│
└── README.md
```

---

# 🚀 Installation et configuration

Suivez les étapes suivantes pour exécuter le projet localement.

---

## 1. Cloner le dépôt

```bash
git clone https://github.com/LogiStock-Team/LogiStock_PFE_2026.git
```

Accéder au dossier :

```bash
cd LogiStock_PFE_2026
```

---

# Configuration Backend

Accéder au dossier backend :

```bash
cd backend
```

Installer les dépendances :

```bash
mvn clean install
```

Lancer l'application Spring Boot :

```bash
mvn spring-boot:run
```

Serveur Backend :

```text
http://localhost:8080
```

---

# Configuration Frontend

Ouvrir un nouveau terminal :

```bash
cd frontend
```

Installer les dépendances :

```bash
npm install
```

Lancer l'application :

```bash
npm run dev
```

Serveur Frontend :

```text
http://localhost:5173
```

---

# ⚙️ Configuration de la base de données

Le projet utilise MySQL.

Configuration nécessaire :

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/logistock
spring.datasource.username=root
spring.datasource.password=votre_mot_de_passe
```

Avant le lancement :

- Créer la base de données
- Configurer les accès MySQL
- Démarrer le serveur MySQL

---

# 🔒 Sécurité

LogiStock intègre plusieurs mécanismes de sécurité :

## Authentification

- Authentification basée sur JWT
- Système de connexion sécurisé
- Protection des API

## Autorisation

- Gestion des accès par rôles (RBAC)
- Gestion des permissions
- Accès limité selon le rôle utilisateur

## Protection des données

- Chiffrement des mots de passe
- Validation des requêtes
- Communication sécurisée entre les couches

---

# 📈 Perspectives d'évolution

Les améliorations possibles :

- 📱 Application mobile
- 🔔 Notifications en temps réel
- 📊 Tableau de bord analytique avancé
- 🤖 Prévision intelligente de la demande
- 🏢 Gestion multi-entrepôts
- 📍 Suivi des livraisons en temps réel
- ☁️ Déploiement Cloud
- 🔄 Sauvegardes automatisées

---

# 👨‍💻 Équipe de développement
## Projet de Fin d'Études (PFE)

Réalisé par :

- Safaa Mounkid
- Marwa Maqsoudi
- Meryem Mazzi

---

# 📜 Licence

Ce projet a été développé dans un cadre académique dans le cadre d'un Projet de Fin d'Études (PFE).

Tous droits réservés © 2026.
