### **Description du projet Artisapp :**

Artisapp est une **application web** conçue pour permettre aux artisans de présenter, gérer et vendre leurs produits artisanaux en toute sécurité. L'objectif principal est de valoriser les produits artisanaux locaux à travers une plateforme intuitive, attrayante et facile à naviguer.

---

### **Technologies utilisées :**

1. **Frontend :**
   - Framework : **Next.js**
   - Langages : **JavaScript** et **TypeScript**
   - UI/UX : **SCADUI** pour un design moderne et intuitif.

2. **Backend :**
   - Framework : **Express.js** (Node.js)
   - Langages : **JavaScript** et **TypeScript**
   - Création d'API RESTful pour gérer les opérations backend.

3. **Base de données :**
   - **MySQL** : Pour stocker et gérer les données structurées des utilisateurs, des produits et des commandes.

---

### **Principales fonctionnalités :**

1. **Création de profils artisans :**
   - Inscription et personnalisation des profils par les artisans.
   - Ajout d'informations sur leurs activités et leurs produits.

2. **Catalogue de produits :**
   - Gestion facile des produits : ajout, modification, suppression.
   - Présentation des produits avec images, descriptions et prix.

3. **Paiement sécurisé :**
   - Intégration de plateformes comme **Stripe** ou **PayPal** pour des transactions fiables.

4. **Gestion des commandes :**
   - Suivi des commandes en temps réel.
   - Notifications pour les états des commandes (nouvelle, en traitement, expédiée, livrée).

5. **Tableau de bord pour les artisans :**
   - Suivi des ventes, des produits populaires et des performances générales.

6. **Espace clients :**
   - Gestion des comptes clients, historique des commandes et produits favoris.

7. **Navigation intuitive :**
   - Design responsive et facile à utiliser, adapté aux mobiles et ordinateurs.

8. **Recherche et filtrage :**
   - Recherche par catégories, prix, localisation ou mots-clés.

9. **Section avis et recommandations :**
   - Les clients peuvent laisser des avis et des évaluations sur les produits.

10. **Section informative ou blog :**
    - Articles sur l’artisanat local, tutoriels et interviews d’artisans.

11. **Support client intégré :**
    - Système de messagerie ou de support pour aider artisans et clients.

---

### **Pré-requis nécessaires :**

1. **Node.js et npm :**
   - Téléchargez et installez [Node.js](https://nodejs.org/) (version LTS recommandée).
   - npm est inclus avec Node.js.

   Vérifiez leur installation avec les commandes :

   ```bash
   node -v
   npm -v
   ```

2. **MySQL :**
   - Installez et configurez MySQL sur votre machine.
   - Créez une base de données pour le projet.

3. **Éditeur de code :**
   - Utilisez un éditeur comme **Visual Studio Code** ([télécharger ici](https://code.visualstudio.com/)).

4. **Git :**
   - Installez **Git** pour cloner le dépôt ([télécharger ici](https://git-scm.com/)).

5. **Gestionnaire de packages :**
   - Utilisez **npm** ou **yarn** pour installer les dépendances du projet.

---

### **Commandes pour télécharger et exécuter le projet :**

1. **Cloner le dépôt :**
   Ouvrez un terminal et exécutez :

   ```bash
   git clone https://github.com/Djennhya/Artisapp.git
   ```

2. **Accéder au dossier du projet :**

   ```bash
   cd Artisapp
   ```

3. **Installer les dépendances :**

   ```bash
   npm install
   ```

   ou, si vous utilisez Yarn :

   ```bash
   yarn install
   ```

4. **Configurer les variables d’environnement :**
   - Créez un fichier **`.env`** à la racine du projet.
   - Ajoutez-y les informations nécessaires comme la configuration de la base de données, les clés API, etc.
   - Consultez un fichier `.env.example` s'il existe pour des exemples.

5. **Démarrer le serveur en mode développement :**

   ```bash
   npm run dev
   ```

   ou, si vous utilisez Yarn :

   ```bash
   yarn dev
   ```

6. **Accéder à l’application :**
   Ouvrez [http://localhost:3000](http://localhost:3000) dans votre navigateur.

7. **Arborescence du projet Artisapp :**

   Artisapp/
├── backend/                    # Serveur Express.js
│   ├── config/                 # Fichiers de config (base de données, etc.)
│   │   └── db.js
│   ├── controllers/            # Logique métier
│   ├── models/                 # Modèles MySQL (ORM ou raw SQL)
│   ├── routes/                 # Routes API Express
│   ├── middleware/             # Auth, validation, gestion des erreurs
│   ├── utils/                  # Fonctions utilitaires
│   └── server.js              # Point d’entrée backend
│
├── frontend/                   # App Next.js
│   ├── components/             # Composants réutilisables (UI, cartes, etc.)
│   ├── pages/                  # Pages Next.js (accueil, produits, profil…)
│   ├── styles/                 # Fichiers SCSS/CSS ou SCADUI
│   ├── services/               # Appels API (axios/fetch)
│   ├── context/                # Authentification, panier, etc.
│   ├── utils/                  # Fonctions d’aide (formattage, etc.)
│   ├── public/                 # Images statiques
│   └── next.config.js
│
├── .env
├── package.json
└── README.md

