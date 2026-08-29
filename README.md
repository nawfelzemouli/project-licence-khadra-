# 🌿 KHADRA - E-Commerce & Management System

Bienvenue sur **Khadra**, une application web complète de commerce en ligne et de gestion dédiée à une pépinière. Ce projet inclut à la fois une vitrine pour les clients et un tableau de bord complet pour les gérants.

## 🚀 Fonctionnalités

### 🛍️ Espace Client
- Consultation du catalogue complet des plantes.
- Recherche avancée par nom, espèce ou catégorie.
- Système de panier d'achat intuitif.
- Validation de commande avec vérification des stocks en temps réel.
- Suivi de l'historique des commandes.
- Gestion du profil et des informations personnelles.

### ⚙️ Espace Administration
- **Gestion des Plantes :** Ajouter (avec upload d'image), modifier, et supprimer des plantes du catalogue.
- **Gestion des Stocks :** Historique des mouvements (entrées/sorties) et suivi des emplacements (serre, extérieur, etc.).
- **Gestion des Ventes :** Suivi de toutes les commandes et mise à jour de leur statut (en attente, payé, etc.).
- **Statistiques :** Tableau de bord générant le chiffre d'affaires, les bénéfices et le nombre de ventes avec filtres par mois/année.
- **Utilisateurs :** Gestion des comptes et attribution des rôles (Administrateur, Vendeur, Client).

## 🛠️ Technologies Utilisées
- **Backend :** Node.js, Express.js
- **Base de données :** SQLite (via `better-sqlite3`)
- **Frontend :** HTML/CSS (Moteur de template EJS), Bootstrap
- **Authentification :** `express-session`, `bcryptjs` (Hashage des mots de passe)
- **Gestion de fichiers :** `multer` (Upload des images de plantes)

## 📦 Installation et Lancement

1. Cloner le projet ou extraire les fichiers.
2. Installer les dépendances nécessaires :
   ```bash
   npm install
   ```
3. Lancer l'application en mode développement :
   ```bash
   npm run dev
   ```
   *(Note : La base de données `pepiniere.db` et les données de test sont générées automatiquement au premier lancement).*
4. Ouvrir le navigateur et accéder à l'adresse : **http://localhost:3001**

## 🔑 Comptes de Test (Générés automatiquement)

- **Administrateur** : `admin@pepiniere.com` | Mot de passe : `password123`
- **Vendeur** : `mohamed@pepiniere.com` | Mot de passe : `password123`
- **Client** : `karim@client.com` | Mot de passe : `password123`
