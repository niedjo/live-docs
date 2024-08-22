
# Live Docs

**Live Docs** est une application web collaborative conçue pour la saisie de documents en temps réel, similaire à Google Docs ou Office Word. Profitez d'une expérience de rédaction fluide, avec des fonctionnalités de collaboration en direct et une interface moderne.

## 🔗 Lien du site

Visitez le site : [Live Docs](https://live-docs.onrender.com) *(Remplacez par le lien réel une fois le déploiement effectué.)*

## ✨ Fonctionnalités

- 📝 **Édition de Documents en Temps Réel** : Créez et modifiez des documents simultanément avec d'autres utilisateurs.
- 👥 **Authentification Sécurisée** : Utilisez Clerk pour une gestion des utilisateurs simple et sécurisée.
- 📄 **Fonctionnalités Avancées d'Édition** : Profitez de fonctionnalités de traitement de texte comparables à celles de Google Docs ou Office Word.
- 🎨 **Thèmes Personnalisables** : Choisissez parmi plusieurs thèmes pour une interface qui vous ressemble.
- 🌐 **Interface Moderne et Responsive** : Conçu avec Tailwind CSS pour une expérience utilisateur optimale sur tous les appareils.

## 🚀 Démarrage

### Prérequis

Avant de commencer, assurez-vous d'avoir les éléments suivants :

- [Node.js](https://nodejs.org/en/) (Version 18 ou supérieure)
- [npm](https://www.npmjs.com/) ou [yarn](https://yarnpkg.com/)
- Clé API Clerk pour la gestion des utilisateurs (créez un compte sur [Clerk](https://clerk.dev/)).

### Installation

1. Clonez le repository :
   ```bash
   git clone https://github.com/your-username/live-docs.git
   cd live-docs
   ```

2. Installez les dépendances :
   ```bash
   npm install
   ```
   ou
   ```bash
   yarn install
   ```

### Configuration de l'authentification Clerk

Créez un fichier `.env.local` à la racine de votre projet et ajoutez-y les clés nécessaires pour configurer Clerk :

```env
NEXT_PUBLIC_CLERK_FRONTEND_API=your-clerk-frontend-api
CLERK_API_KEY=your-clerk-api-key
```

Remplacez `your-clerk-frontend-api` et `your-clerk-api-key` par vos propres valeurs.

### Démarrer le serveur de développement

Pour lancer l'application en mode développement, exécutez la commande suivante :

```bash
npm run dev
```

L'application sera accessible à l'adresse [http://localhost:3000](http://localhost:3000).

### Construction pour la production

Pour créer une version optimisée de l'application, utilisez la commande :

```bash
npm run build
```

Ensuite, vous pouvez démarrer l'application optimisée avec :

```bash
npm start
```

## 🛠️ Technologies Utilisées

- **[Next.js](https://nextjs.org/)** - Framework React pour les applications web.
- **[React](https://reactjs.org/)** - Bibliothèque JavaScript pour créer des interfaces utilisateurs.
- **[Tailwind CSS](https://tailwindcss.com/)** - Framework CSS utilitaire pour un design rapide.
- **[Clerk](https://clerk.dev/)** - Solution d'authentification et gestion des utilisateurs.
- **[Liveblocks](https://liveblocks.io/)** - API pour la collaboration en temps réel.
- **[Lexical](https://lexical.dev/)** - Éditeur de texte extensible pour le Web.

## 📦 Structure du projet

```
live_docs/
├── app/              # Pages Next.js
├── public/           # Fichiers publics (images, icônes, etc.)
├── components/       # Composants React
├── lib/              # Bibliothèques et configurations spécifiques
├── tsconfig.json     # Configuration TypeScript
├── package.json      # Dépendances et scripts
└── README.md         # Documentation du projet
```

## 💡 À propos

**Live Docs** est conçu pour les équipes et les individus qui souhaitent collaborer en temps réel sur des documents tout en bénéficiant d'une interface moderne et sécurisée.

## 📄 License

Ce projet est sous licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus de détails.

---

**Live Docs** - Collaborative Real-Time Document Editing for Teams.