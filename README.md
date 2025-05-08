# TrustBadge App

Implémentation du système de badges de confiance pour les entreprises, permettant aux clients de laisser des avis et aux entreprises de gérer leur réputation.

## Fonctionnalités

- Système de notation et d'avis
- Support du stockage hors ligne
- Support multilingue (FR/EN)
- Support des thèmes clair/sombre
- Synchronisation automatique des avis

## Installation

1. Cloner le dépôt :
```bash
git clone https://github.com/Affouetemma/trustbadge-app.git
cd trustbadge-app
```

2. Installer les dépendances :
```bash
npm install
```

3. Démarrer le serveur de développement :
```bash
npm run dev
```

## Variables d'Environnement

Créez un fichier `.env` à la racine du projet avec les variables suivantes :

```env
VITE_API_URL=votre_url_api
VITE_API_KEY=votre_cle_api
```

## Développement

- `npm run dev` - Démarrer le serveur de développement
- `npm run build` - Construire pour la production
- `npm run preview` - Prévisualiser la version de production
