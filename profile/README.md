# 🎵 MelodyHue

**Transformez votre musique Spotify en couleurs dynamiques pour vos overlays de streaming !**

## 🌟 Qu'est-ce que MelodyHue ?

MelodyHue est une application web innovante qui synchronise vos couleurs d'overlay avec votre musique Spotify en temps réel. Parfait pour les streamers, créateurs de contenu et passionnés de musique qui souhaitent ajouter une dimension visuelle à leur expérience audio.

### ✨ Fonctionnalités principales

- 🎨 **Extraction de couleurs automatique** depuis les pochettes d'albums Spotify
- 🔴 **Overlays personnalisables** avec templates et couleurs dynamiques
- 🔐 **Authentification sécurisée** avec JWT et 2FA optionnel
- � **API publique** pour intégrer vos couleurs dans vos applications
- ⚡ **Temps réel** - Les couleurs changent instantanément avec votre musique
- 📱 **Interface moderne** développée avec Angular 20 et FastAPI

## � Démarrage rapide

### Pour les développeurs

```bash
# Cloner le projet
git clone https://github.com/melodyhue/frontend.git
git clone https://github.com/melodyhue/backend.git

# Configuration du backend (FastAPI)
cd backend
pip install -r requirements.txt
# Configurer vos variables d'environnement
python -m uvicorn app.asgi:app --reload

# Configuration du frontend (Angular)
cd ../frontend
npm install
npm start
```

### Pour les utilisateurs

1. � Connectez votre compte Spotify
2. 🎨 Créez vos overlays personnalisés
3. 🔗 Intégrez l'URL de couleur dans OBS ou votre logiciel de streaming
4. ✨ Profitez des couleurs qui changent avec votre musique !

## 🛠️ Stack technique

### Frontend
- **Angular 20** avec SSR (Server-Side Rendering)
- **TypeScript** strict avec signals et standalone components
- **SCSS** pour le styling
- **Karma + Jasmine** pour les tests

### Backend
- **FastAPI** avec architecture MVC
- **SQLAlchemy 2.0** + PostgreSQL
- **JWT Authentication** avec refresh tokens
- **Docker** pour le déploiement

## 📚 Ressources utiles

- 📖 [Documentation Frontend](https://github.com/melodyhue/frontend/blob/main/README.md)
- 📖 [Documentation Backend](https://github.com/melodyhue/backend/blob/main/README.md)
- 🐛 [Signaler un bug](https://github.com/melodyhue/frontend/issues/new?template=bug_report.md)
- 💡 [Demander une fonctionnalité](https://github.com/melodyhue/frontend/issues/new?template=feature_request.md)

## 🤝 Contribuer

Nous accueillons chaleureusement les contributions ! Voici comment vous pouvez aider :

1. 🍴 **Fork** le projet
2. 🌿 **Créez** une branche pour votre fonctionnalité (`git checkout -b feature/AmazingFeature`)
3. ✅ **Commitez** vos changements (`git commit -m 'Add some AmazingFeature'`)
4. 📤 **Push** vers la branche (`git push origin feature/AmazingFeature`)
5. 🔃 **Ouvrez** une Pull Request

### Guidelines de contribution

- Suivez les conventions de code existantes (Angular/TypeScript pour le frontend, Python/FastAPI pour le backend)
- Ajoutez des tests pour vos nouvelles fonctionnalités
- Mettez à jour la documentation si nécessaire
- Utilisez des messages de commit descriptifs

##  Communauté

<!-- - 💬 [Discord](https://discord.melodyhue.com) - Rejoignez notre communauté -->
- 🐦 [Twitter](https://twitter.melodyhue.com) - Suivez nos actualités
- 📧 [Email](mailto:contact@melodyhue.com) - Contactez-nous

## 📄 Licence

Ce projet est sous licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus de détails.

---

<div align="center">
  <strong>Fait avec ❤️ par l'équipe MelodyHue</strong>
</div>
