# LifeTracker 🌿

Une application minimaliste et puissante pour suivre vos habitudes, gérer vos tâches et rester concentré. Conçue pour être fluide, belle et efficace sur mobile.

## Fonctionnalités ✨

- **📅 Vue Aujourd'hui** : Un tableau de bord clair de votre journée avec un score de productivité.
- **🍅 Focus Timer** : Un minuteur Pomodoro intégré pour des sessions de travail profond.
- **✅ Tâches** : Gestionnaire de tâches simple et efficace avec priorités.
- **🔥 Habitudes** : Suivi d'habitudes avec visualisation de séquences (streaks).
- **📖 Journal** : Espace pour la gratitude, les intentions et l'écriture libre.
- **📱 Optimisé Mobile** : Interface tactile, retours haptiques et animations fluides.
- **💾 100% Local** : Vos données restent sur votre appareil (persistance native).

## Tech Stack 🛠️

- **Framework** : [React](https://react.dev/) + [Vite](https://vitejs.dev/)
- **Mobile** : [Capacitor](https://capacitorjs.com/) (Android & iOS)
- **Styling** : CSS Modules + Utilitaires (inspiré de Tailwind)
- **Icons** : Lucide React
- **Animations** : CSS Transitions & Keyframes

## Installation & Démarrage 🚀

### Prérequis

- Node.js (v18+)
- Android Studio (pour Android)
- Xcode (pour iOS, sur macOS uniquement)

### Développement Web

Pour lancer l'application dans votre navigateur :

```bash
# Installer les dépendances
npm install

# Lancer le serveur de développement
npm run dev
```

### Mobile (Android)

Pour lancer l'application sur un émulateur ou un appareil Android :

```bash
# Synchroniser le projet Capacitor
npx cap sync

# Ouvrir Android Studio
npx cap open android
```

## Structure du Projet ​​​​​​​​​​📂

- `src/components/tabs` : Les écrans principaux (Today, Focus, Tasks, etc.).
- `src/components/ui` : Composants réutilisables (Card, Pill, Ring...).
- `src/context` : Gestion d'état global (DataContext).
- `src/hooks` : Hooks personnalisés (useStorage, etc.).
- `src/utils` : Helpers et constantes.

## Licence 📄

Ce projet est sous licence MIT. Sentez-vous libre de le modifier et de l'améliorer !
