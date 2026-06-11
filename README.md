# Exercice Workflow GitHub Actions

![Commit Message](https://github.com/azertyop-e/devOps/actions/workflows/commit-message.yml/badge.svg)
![Generate Image](https://github.com/azertyop-e/devOps/actions/workflows/generate-image.yml/badge.svg)
![Discord](https://github.com/azertyop-e/devOps/actions/workflows/discord-notification.yml/badge.svg)
![Comment](https://github.com/azertyop-e/devOps/actions/workflows/comment-on-commit.yml/badge.svg)
![Update Badges](https://github.com/azertyop-e/devOps/actions/workflows/update-badges.yml/badge.svg)

![GitHub release](https://img.shields.io/github/v/release/azertyop-e/devOps)
![Contributors](https://img.shields.io/github/contributors/azertyop-e/devOps)
![Stars](https://img.shields.io/github/stars/azertyop-e/devOps)
![Last commit](https://img.shields.io/github/last-commit/azertyop-e/devOps)

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

1. **Secrets GitHub à configurer** :
   - `DYNAPICTURES_API_KEY` : clé API DynaPictures (Ex. 02)
   - `DYNAPICTURES_TEMPLATE_UID` : UID du template DynaPictures (Ex. 02)
   - `DISCORD_WEBHOOK_URL` : URL du webhook Discord (Ex. 03)

2. **Activer GitHub Pages** → Settings → Pages → source : branche `gh-pages`

### Utilisation

Poussez vos commits sur la branche `main` pour déclencher les workflows automatiquement.

Pour déclencher manuellement : allez dans l'onglet "Actions" et cliquez sur le workflow souhaité.

---

Généré avec Git Workflow Manager
