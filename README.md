# Système de gestion des commandes et livraisons

Ce projet contient à la fois le **frontend** et le **backend** d'un système de gestion des commandes, livraisons, paiements et clients.

## 🧰 Technologies utilisées

### Frontend
- **Next.js 14** (React Framework)
- **TypeScript**
- **Tailwind CSS** (pour le styling)
- **Axios** (pour la communication avec le backend)

### Backend
- **Java 17**
- **Spring Boot** (Framework pour le backend)
- **Spring Data JPA** (Accès aux données)
- **MySQL** (Base de données)
- **Maven** (Outil de gestion de dépendances et de build)

## 🚀 Fonctionnalités principales

### Frontend
- Interface utilisateur pour gérer les commandes, les livraisons, les paiements et les clients.
- Permet de visualiser, créer et mettre à jour les commandes.
- Interface de gestion des informations des clients et des livraisons.
- Vue pour suivre l’état des livraisons et afficher l’historique des commandes.

### Backend
- API REST exposée pour gérer les commandes, les produits, les clients, les paiements et les transporteurs.
- **CRUD** pour gérer les entités Commandes, Produits, Clients, Paiements, Livraisons et Transporteurs.
- Création et validation des bons de commande.
- Mise à jour automatique des stocks à chaque livraison.
- Historique des commandes pour chaque client.
- Suivi des livraisons avec des informations sur le statut et la date de livraison.

## 📥 Installation

### 1. Frontend - Next.js

#### Prérequis
- Node.js >= 16.x
- npm (installé avec Node.js)

#### Étapes d’installation
1. Clonez le dépôt du frontend :
   ```bash
   git clone https://github.com/Yassinekacem/commande-livraison-frontend.git
