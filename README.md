# tyberzan.github.io
Front du projet CDA 

# CDASelectionProject

Ce projet est une application web qui affiche des blagues aléatoires en utilisant une API backend. L'application est déployée sur GitHub Pages et le backend est déployé sur Render.

## Fonctionnalités

- Afficher une blague aléatoire en cliquant sur un bouton.
- Utilisation de l'API pour récupérer des blagues depuis une base de données.
- Gestion des erreurs et affichage des messages d'erreur appropriés.

## Prérequis

- Node.js
- npm (Node Package Manager)

## Installation

1. Clonez le dépôt :

   git clone https://github.com/tyberzan/CDASelectionProject.git cd CDASelectionProject

2. Installez les dépendances :

  npm install


## Utilisation

1. Démarrez le serveur backend :

  node index.js

2. Ouvrez votre navigateur et accédez à l'URL suivante pour voir l'application en action :

   https://tyberzan.github.io


## Dépendances

- express
- body-parser
- cors
- sequelize
- sqlite3
- swagger-jsdoc
- swagger-ui-express

## API

L'API backend fournit plusieurs endpoints pour gérer les blagues. Voici quelques exemples :

- `GET /v2/blagues/random` : Récupérer une blague aléatoire.
- `POST /v2/AddJoke` : Ajouter une nouvelle blague.
- `GET /v2/blagues/:id` : Récupérer une blague par ID.
- `DELETE /v2/blagues/DeleteJoke/:id` : Supprimer une blague par ID.

## Configuration CORS

Le serveur backend est configuré pour autoriser les requêtes provenant de `https://tyberzan.github.io` en utilisant le middleware `cors`.

## Swagger

L'API est documentée à l'aide de Swagger. Vous pouvez accéder à la documentation Swagger à l'URL suivante :


## Dépendances

- express
- body-parser
- cors
- sequelize
- sqlite3
- swagger-jsdoc
- swagger-ui-express

## API

L'API backend fournit plusieurs endpoints pour gérer les blagues. Voici quelques exemples :

- `GET /v2/blagues/random` : Récupérer une blague aléatoire.
- `POST /v2/AddJoke` : Ajouter une nouvelle blague.
- `GET /v2/blagues/:id` : Récupérer une blague par ID.
- `DELETE /v2/blagues/DeleteJoke/:id` : Supprimer une blague par ID.

## Configuration CORS

Le serveur backend est configuré pour autoriser les requêtes provenant de `https://tyberzan.github.io` en utilisant le middleware `cors`.

## Swagger

L'API est documentée à l'aide de Swagger. Vous pouvez accéder à la documentation Swagger à l'URL suivante :

https://cdaselectionproject.onrender.com/api-docs/

## Auteur

- [Roman](https://github.com/tyberzan)

## Licence

Ce projet est sous licence ISC.

