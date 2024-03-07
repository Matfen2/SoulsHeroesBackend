# Souls Heroes

Second Single Page Application



## Authors

- [@matfen](https://github.com/Matfen2)


## Deployment

Déployer sur le site heroku

## Features
- API CRUD OPERATIONS (SEARCH/SUBSCRIBE)
- CONNEXION AVEC LA BASE DE DONNEES HORS LOCAL (heroku/hostinger)


## Installation

Créer un projet avec le dossier "backend"

Déploiement via heroku avec 
    heroku login
    git init
    git add .
    git commit -m "deploy-backend"
    heroku create "souls-heroes-bacekdn"
    git push heroku master
    heroku open
## Run Locally

Initialiser le git
```bash
  git init 
  git add .
```

Faire le commit 
```bash
  git commit -m "deploy-site" avec la description de chaque commit
```

Aller à la source du projet

```bash
  cd "H:\Développeur Web\Backend\Souls-Heroes-Backend"
```

Installer les dépendences

```bash
  npm init -y
  npm install express cors path mysql nodemon dotenv body-parser
```

Allumer le serveur

```bash
  nnodemon server.js
```


## Tech Stack

**Server:** Express, NodeJs, MYSQL, PHPMyAdmin, POSTMAN


