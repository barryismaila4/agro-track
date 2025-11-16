
## 🚀 Installation et Démarrage

### Prérequis
- Java 17+
- MySQL 8.0+
- Node.js 16+
- Angular CLI

### Configuration Backend
1. Clonez le repository
2. Configurez la base de données MySQL
3. Modifiez `application.properties` avec vos credentials
4. Lancez l'application Spring Boot

### Configuration Frontend
1. Allez dans le dossier `agrotrack-frontend`
2. `npm install`
3. `ng serve`

## 📚 API Endpoints

### Authentification
- `POST /api/auth/register` - Inscription
- `POST /api/auth/login` - Connexion
- `GET /api/auth/me` - Profil utilisateur

### Gestion des Plantes
- `GET /api/plants` - Liste des plantes
- `POST /api/plants` - Ajouter une plante
- `PUT /api/plants/{id}` - Modifier une plante
- `DELETE /api/plants/{id}` - Supprimer une plante
- `POST /api/plants/{id}/water` - Marquer comme arrosée

### Système de Notifications
- `GET /api/notifications` - Toutes les notifications
- `GET /api/notifications/unread` - Notifications non lues
- `POST /api/notifications` - Créer une notification
- `PUT /api/notifications/{id}/read` - Marquer comme lue

## 🌟 Pourquoi AgroTrack ?

### Pour les Jardiniers Amateurs
- **Simplifiez** la gestion de votre jardin
- **N'oubliez plus** les dates importantes d'entretien
- **Suivez** l'évolution de vos plantes

### Pour les Professionnels
- **Optimisez** votre temps de travail
- **Centralisez** vos informations plantes
- **Automatisez** les rappels d'entretien

## 🎯 Roadmap

- [ ] Application mobile React Native
- [ ] Intelligence Artificielle pour diagnostics plantes
- [ ] Communauté et partage entre utilisateurs
- [ ] Calendrier lunaire intégré
- [ ] Module météo intelligent

## 🤝 Contribution

Les contributions sont les bienvenues ! N'hésitez pas à :
- Signaler des bugs
- Proposer de nouvelles fonctionnalités
- Soumettre des pull requests

## 📄 Licence

Ce projet est sous licence MIT. Voir le fichier `LICENSE` pour plus de détails.

---

**AgroTrack** - Parce que chaque plante mérite une attention particulière 🌟