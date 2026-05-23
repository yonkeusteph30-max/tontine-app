# Tontine Management Application

Une application web responsive complète pour gérer les tontines globalement avec une base de données robuste.

## 🚀 Fonctionnalités

- **Gestion des membres**: Ajouter, modifier, supprimer des membres
- **Gestion des contributions**: Tracker les paiements et contributions
- **Gestion des tours**: Organiser les distributions
- **Historique et rapports**: Suivi complet des transactions
- **Authentification sécurisée**: Connexion par rôles (Admin, Trésorier, Membre)
- **Interface responsive**: Mobile, tablet et desktop
- **Notifications**: Alertes en temps réel

## 🛠️ Stack Technique

### Frontend
- React.js
- Tailwind CSS
- Axios
- Chart.js pour les statistiques

### Backend
- Node.js / Express.js
- PostgreSQL
- JWT pour l'authentification
- Redis pour le cache

### Infrastructure
- Docker & Docker Compose
- Nginx (reverse proxy)

## 📦 Installation

### Avec Docker Compose (Recommandé)

```bash
docker-compose up -d
```

L'application sera accessible à:
- Frontend: http://localhost:3000
- Backend API: http://localhost:8000

### Installation locale

Voir les README individuels dans les dossiers `/frontend` et `/backend`.

## 📚 Documentation

- [API Documentation](./backend/README.md)
- [Frontend Documentation](./frontend/README.md)
- [Database Schema](./backend/docs/schema.md)

## 👥 Contributeurs

Créé par: yonkeusteph30-max

## 📄 Licence

MIT
