# Application Web de Suivi de Chantier

Application web permettant la gestion et le suivi des projets de construction.

## Fonctionnalités principales

- Gestion des utilisateurs et des rôles
- Suivi des projets de construction
- Gestion des tâches et des incidents
- Gestion documentaire
- Rapports et notifications

## Architecture technique

### Frontend
- React.js
- Material-UI pour l'interface utilisateur
- Redux pour la gestion d'état

### Backend
- Node.js avec Express
- PostgreSQL comme base de données
- JWT pour l'authentification

## Structure du projet

```
├── client/             # Frontend React
│   ├── src/
│   │   ├── components/ # Composants React
│   │   ├── pages/      # Pages de l'application
│   │   ├── services/   # Services API
│   │   └── store/      # État Redux
├── server/             # Backend Node.js
│   ├── src/
│   │   ├── controllers/
│   │   ├── models/
│   │   ├── routes/
│   │   └── services/
└── docs/              # Documentation
```

## Installation

```bash
# Cloner le repository
git clone https://github.com/Chocotomtom/construction-site-tracker.git

# Installer les dépendances
cd construction-site-tracker
npm install

# Lancer en développement
npm run dev
```

## Contribution

Pour contribuer au projet :
1. Créez une branche (`git checkout -b feature/AmazingFeature`)
2. Committez vos changements (`git commit -m 'Add some AmazingFeature'`)
3. Pushez sur la branche (`git push origin feature/AmazingFeature`)
4. Ouvrez une Pull Request