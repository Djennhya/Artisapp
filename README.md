# **Artisapp**

Artisapp est une application web qui permet aux artisans de présenter et vendre leurs produits en toute sécurité. Cette plateforme vise à valoriser les produits artisanaux locaux grâce à une navigation intuitive et des pages attrayantes.

---

## **Architecture du projet**

Le projet est organisé en deux principales parties : **backend** (serveur Express.js) et **frontend** (application Next.js). Voici l'arborescence du projet pour mieux comprendre sa structure :

```plaintext
Artisapp/
├── backend/                    # Serveur Express.js
│   ├── config/                 # Fichiers de config (base de données, etc.)
│   │   └── db.js
│   ├── controllers/            # Logique métier
│   ├── models/                 # Modèles MySQL (ORM ou raw SQL)
│   ├── routes/                 # Routes API Express
│   ├── middleware/             # Auth, validation, gestion des erreurs
│   ├── utils/                  # Fonctions utilitaires
│   └── server.js               # Point d’entrée backend
│
├── frontend/                   # App Next.js
│   ├── components/             # Composants réutilisables (UI, cartes, etc.)
│   ├── pages/                  # Pages Next.js (accueil, produits, profil…)
│   ├── styles/                 # Fichiers SCSS/CSS ou SCADUI
│   ├── services/               # Appels API (axios/fetch)
│   ├── context/                # Authentification, panier, etc.
│   ├── utils/                  # Fonctions d’aide (formattage, etc.)
│   ├── public/                 # Images statiques
│   └── next.config.js          # Configuration Next.js
│
├── .env                        # Variables d’environnement
├── package.json                # Dépendances du projet
└── README.md                   # Documentation du projet
```

---

## **Technologies utilisées**

### **Frontend :**
- **Framework :** Next.js
- **Langages :** JavaScript, TypeScript
- **UI Design :** SCADUI

### **Backend :**
- **Framework :** Express.js (Node.js)
- **Langages :** JavaScript, TypeScript
- **Base de données :** MySQL

---

## **Fonctionnalités principales**

- **Création de profils artisans** : Présentation des artisans et de leurs produits.
- **Catalogue de produits** : Ajout, modification et suppression de produits.
- **Paiement sécurisé** : Intégration de services comme Stripe ou PayPal.
- **Gestion des commandes** : Suivi et notifications en temps réel.
- **Tableau de bord** : Suivi des performances et des ventes.
- **Recherche et filtrage avancés** : Par catégories, prix, localisation.
- **Support client intégré** : Messagerie ou support pour artisans et clients.

---

## **Installation et exécution**

### **Prérequis :**
- [Node.js](https://nodejs.org/) (version LTS recommandée)
- [MySQL](https://www.mysql.com/)
- Un gestionnaire de paquets comme **npm** ou **yarn**

### **Étapes :**

1. **Cloner le projet :**
   ```bash
   git clone https://github.com/Djennhya/Artisapp.git
   cd Artisapp
   ```

2. **Installer les dépendances :**
   ```bash
   npm install
   ```

3. **Configurer les variables d'environnement :**
   - Créez un fichier `.env` à la racine du projet.
   - Ajoutez les configurations nécessaires (exemple : base de données, clés API).

4. **Démarrer le backend :**
   ```bash
   cd backend
   npm start
   ```

5. **Démarrer le frontend :**
   ```bash
   cd frontend
   npm run dev
   ```

6. **Accéder à l'application :**
   - Ouvrez votre navigateur et rendez-vous sur [http://localhost:3000](http://localhost:3000).

---

## **Contribuer**

Les contributions sont les bienvenues ! Si vous souhaitez participer au projet, suivez ces étapes :
1. Forkez le dépôt.
2. Créez une branche pour vos modifications.
3. Effectuez un **pull request**.
