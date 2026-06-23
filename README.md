<p align="center">
  <img src="https://drive.google.com/uc?id=1EvzkKywXmq366k6nRjM9hSKySdmh6ko9" width="250" alt="LogiStock Logo"/>
</p>
<p align="center">
B2B Stock and Logistics Management Platform
</p>

<br>

---

<br>
# 🌍 Language / Langue

- [🇬🇧 English Version](#-logistock)
- [🇫🇷 Version Française](#-version-francaise)

---

<p align="center">
  <img src="https://img.shields.io/badge/React-Frontend-blue" />
  <img src="https://img.shields.io/badge/SpringBoot-Backend-green" />
  <img src="https://img.shields.io/badge/MySQL-Database-orange" />
  <img src="https://img.shields.io/badge/JWT-Authentication-red" />
</p>

# 🇬🇧 LogiStock

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

# 🇫🇷 Version Francaise

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
# 🇬🇧 Authentication & Access Management

## 🔐 Login Page

The login page allows users to securely access the platform according to their assigned role.

Features:

- Secure authentication
- JWT-based session management
- Role-based redirection
- Protected routes

![Login](https://drive.google.com/uc?id=1hOVz9orLu8gSlNmqUKDBgLLJ54mjZAfC)

---

## 📝 Registration Page

New users can create an account and request access to the platform.

Features:

- User registration
- Account creation request
- Validation workflow
- Secure credential management

![Registration](https://drive.google.com/uc?id=1BbJZkM4D1Aro07IqIJ3iHG2qrx51JKOJ)

---

# 👤 Roles & Digital Signature

The platform implements Role-Based Access Control (RBAC) to ensure that each user accesses only the functionalities related to their role.

In addition, LogiStock integrates a digital signature system that enables secure validation of contracts and important documents.

Features:

- Role management
- Permission assignment
- Secure document validation
- Electronic signature workflow
- Access control

![Roles and Signature](https://drive.google.com/uc?id=1dfzBYG0_ps58sKiVbNJBpwT-uAo3wup9)

---

# 📄 Invoice Management

LogiStock automatically generates invoices associated with completed orders.

Features:

- Invoice generation
- Order-to-invoice conversion
- Invoice tracking
- Downloadable invoices
- Centralized invoice management

![Invoice](https://drive.google.com/uc?id=1CGyw3PlpEXoKJbc2-T72tmWyo25KBF5C)

---

# 🇫🇷 Authentification et Gestion des Accès

## 🔐 Page de connexion

La page de connexion permet aux utilisateurs d'accéder à la plateforme de manière sécurisée selon leur rôle.

Fonctionnalités :

- Authentification sécurisée
- Gestion des sessions avec JWT
- Redirection selon le rôle
- Protection des routes

![Connexion](https://drive.google.com/uc?id=1hOVz9orLu8gSlNmqUKDBgLLJ54mjZAfC)

---

## 📝 Page d'inscription

Les nouveaux utilisateurs peuvent créer un compte et demander l'accès à la plateforme.

Fonctionnalités :

- Création de compte
- Demande d'inscription
- Processus de validation
- Gestion sécurisée des identifiants

![Inscription](https://drive.google.com/uc?id=1BbJZkM4D1Aro07IqIJ3iHG2qrx51JKOJ)

---

# 👤 Gestion des rôles et Signature électronique

La plateforme implémente un système de contrôle d'accès basé sur les rôles (RBAC) afin que chaque utilisateur accède uniquement aux fonctionnalités qui lui sont autorisées.

LogiStock intègre également un système de signature électronique permettant la validation sécurisée des contrats et documents importants.

Fonctionnalités :

- Gestion des rôles
- Attribution des permissions
- Validation sécurisée des documents
- Processus de signature électronique
- Contrôle des accès

![Gestion des rôles](https://drive.google.com/uc?id=1dfzBYG0_ps58sKiVbNJBpwT-uAo3wup9)

---

# 📄 Gestion des factures

LogiStock génère automatiquement les factures associées aux commandes validées.

Fonctionnalités :

- Génération automatique des factures
- Conversion commande → facture
- Suivi des factures
- Téléchargement des factures
- Gestion centralisée

![Facture](https://drive.google.com/uc?id=1CGyw3PlpEXoKJbc2-T72tmWyo25KBF5C)

---
# 🇬🇧 User Interfaces & Demonstrations

This section presents the different interfaces provided by LogiStock according to each user role.

Each user has a dedicated workspace with functionalities adapted to their responsibilities.

---

# 🧑‍💼 Supplier Interface

The supplier interface allows suppliers to manage their products, process customer orders, and monitor delivery operations.

![Supplier Interface](https://drive.google.com/uc?id=1IrgT23THbtqrrbSx-QYeFSq13sYOlk8A)

## Features

- Product management
- Stock update
- Order reception
- Delivery tracking
- Invoice generation

---

## 🎥 Demo Video – Supplier View

Watch the supplier workflow demonstration:

https://drive.google.com/file/d/1z-taglKqUk3bOl7pUZqCvxwtLqNhj-7z/view?usp=sharing

---

# 📊 Manager Interface

The manager interface provides tools for supervising inventory and logistics operations.

![Manager Interface](https://drive.google.com/uc?id=1pHruU34ZxZdzmxznhhlUnJIydx50mMsf)

## Features

- Inventory monitoring
- Logistics supervision
- Operation validation
- Order management
- Performance monitoring

---

## 🎥 Demo Video – Manager View

Watch the manager workflow demonstration:

https://drive.google.com/file/d/1flbgS3rr_yNCE6e46GnTgkijznsf3Ckx/view?usp=drive_link

---

# 🛒 Client Interface

The client interface allows customers to browse available products and manage their purchases.

![Client Interface](https://drive.google.com/uc?id=1DUafhG6lbqTeT6inhlVUaaFfDm_lnUOW)

## Features

- Product catalog consultation
- Product search
- Order placement
- Order tracking
- Invoice consultation
- Profile management

---

## 🎥 Demo Video – Client View

Watch the client workflow demonstration:

https://drive.google.com/file/d/1ywNUr1047s2mG4d2Cy64gkyt3HnNV_Mt/view?usp=drive_link

---

# ⚙️ Administrator Interface

The administrator interface provides complete control over the platform configuration and users.

![Administrator Interface](https://drive.google.com/uc?id=15OAAW0OMGIJ2F1PBBJF76xH8TEEYCmQ-)

## Features

- User management
- Role and permission management
- System configuration
- Platform monitoring
- Security management

---

## 🎥 Demo Video – Administrator View

Watch the administrator workflow demonstration:

https://drive.google.com/file/d/1XpTn4Xpwu1JyY_jSefTJ2hSV8s127TFV/view?usp=drive_link

---

# 🇫🇷 Interfaces utilisateurs et démonstrations

Cette partie présente les différentes interfaces proposées par LogiStock selon le rôle de chaque utilisateur.

Chaque acteur possède un espace dédié avec des fonctionnalités adaptées à ses responsabilités.

---

# 🧑‍💼 Interface Fournisseur

L’interface fournisseur permet aux fournisseurs de gérer leurs produits, traiter les commandes reçues et suivre les opérations de livraison.

![Interface Fournisseur](https://drive.google.com/uc?id=1IrgT23THbtqrrbSx-QYeFSq13sYOlk8A)

## Fonctionnalités

- Gestion des produits
- Mise à jour des stocks
- Réception des commandes
- Suivi des livraisons
- Génération des factures

---

## 🎥 Démonstration – Vue Fournisseur

Découvrez le fonctionnement de l’espace fournisseur :

https://drive.google.com/file/d/1z-taglKqUk3bOl7pUZqCvxwtLqNhj-7z/view?usp=sharing

---

# 📊 Interface Gestionnaire

L’interface gestionnaire fournit les outils nécessaires pour superviser les opérations de stock et de logistique.

![Interface Gestionnaire](https://drive.google.com/uc?id=1pHruU34ZxZdzmxznhhlUnJIydx50mMsf)

## Fonctionnalités

- Surveillance des stocks
- Supervision logistique
- Validation des opérations
- Gestion des commandes
- Suivi des performances

---

## 🎥 Démonstration – Vue Gestionnaire

Découvrez le fonctionnement de l’espace gestionnaire :

https://drive.google.com/file/d/1flbgS3rr_yNCE6e46GnTgkijznsf3Ckx/view?usp=drive_link

---

# 🛒 Interface Client

L’interface client permet aux utilisateurs de consulter les produits disponibles et de gérer leurs achats.

![Interface Client](https://drive.google.com/uc?id=1DUafhG6lbqTeT6inhlVUaaFfDm_lnUOW)

## Fonctionnalités

- Consultation du catalogue produit
- Recherche de produits
- Passage de commandes
- Suivi des commandes
- Consultation des factures
- Gestion du profil

---

## 🎥 Démonstration – Vue Client

Découvrez le fonctionnement de l’espace client :

https://drive.google.com/file/d/1ywNUr1047s2mG4d2Cy64gkyt3HnNV_Mt/view?usp=drive_link

---

# ⚙️ Interface Administrateur

L’interface administrateur permet de gérer la configuration globale de la plateforme.

![Interface Administrateur](https://drive.google.com/uc?id=15OAAW0OMGIJ2F1PBBJF76xH8TEEYCmQ-)

## Fonctionnalités

- Gestion des utilisateurs
- Gestion des rôles et permissions
- Configuration du système
- Surveillance de la plateforme
- Gestion de la sécurité

---

## 🎥 Démonstration – Vue Administrateur

Découvrez le fonctionnement de l’espace administrateur :

https://drive.google.com/file/d/1XpTn4Xpwu1JyY_jSefTJ2hSV8s127TFV/view?usp=drive_link

---
# 🏗️ Project Architecture

## 🇬🇧 Architecture Overview

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

## 🇬🇧 Installation Guide

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

# 🇫🇷 Architecture du projet

## Vue générale de l’architecture

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

## Guide d'installation

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

# 👨‍💻 Development Team / Équipe de développement

## 🇬🇧 Final Year Project (PFE)

Developed by:

- Safaa Mounkid
- Marwa Maqsoudi
- Meryem Mazzi

---

## 🇫🇷 Projet de Fin d'Études (PFE)

Réalisé par :

- Safaa Mounkid
- Marwa Maqsoudi
- Meryem Mazzi

---

# 📜 License / Licence

## 🇬🇧

This project was developed for academic purposes as part of a Final Year Project (PFE).

All rights reserved © 2026.

---

## 🇫🇷

Ce projet a été développé dans un cadre académique dans le cadre d'un Projet de Fin d'Études (PFE).

Tous droits réservés © 2026.
