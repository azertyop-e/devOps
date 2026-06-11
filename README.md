# Exercice Workflow GitHub Actions

![Commit Message](https://github.com/OWNER/REPO/actions/workflows/commit-message.yml/badge.svg)
![Generate Image](https://github.com/OWNER/REPO/actions/workflows/generate-image.yml/badge.svg)
![Discord](https://github.com/OWNER/REPO/actions/workflows/discord-notification.yml/badge.svg)
![Comment](https://github.com/OWNER/REPO/actions/workflows/comment-on-commit.yml/badge.svg)
![Update Badges](https://github.com/OWNER/REPO/actions/workflows/update-badges.yml/badge.svg)

![GitHub release](https://img.shields.io/github/v/release/OWNER/REPO)
![Contributors](https://img.shields.io/github/contributors/OWNER/REPO)
![Stars](https://img.shields.io/github/stars/OWNER/REPO)
![Last commit](https://img.shields.io/github/last-commit/OWNER/REPO)

## Exercices GitHub Actions

Pipeline progressif de 5 exercices couvrant les fondamentaux de GitHub Actions.

### Structure du projet

```
exerciceWorkflow/
├── .github/
│   └── workflows/
│       ├── commit-message.yml          # Ex. 01 - Afficher le message du commit
│       ├── generate-image.yml          # Ex. 02 - Générer une image via API DynaPictures
│       ├── discord-notification.yml    # Ex. 03 - Envoyer notification Discord
│       ├── comment-on-commit.yml       # Ex. 04 - Commenter sur le commit
│       └── update-badges.yml           # Ex. 05 - Mettre à jour les badges
├── images/
│   └── .gitkeep
└── README.md
```

### Configuration avant utilisation

1. **Remplacer les placeholders** dans ce fichier :
   - `OWNER` : votre nom d'utilisateur GitHub
   - `REPO` : le nom du dépôt

2. **Pour les exercices 02-04**, configurer les secrets GitHub :
   - `DYNAPICTURES_API_KEY` : votre clé API DynaPictures
   - `DISCORD_WEBHOOK_URL` : URL de votre webhook Discord

3. **Activer GitHub Pages** pour le déploiement des images

### Utilisation

Poussez vos commits sur la branche `main` pour déclencher les workflows automatiquement.

Pour déclencher manuellement : allez dans l'onglet "Actions" et cliquez sur le workflow souhaité.

---

Généré avec Git Workflow Manager
