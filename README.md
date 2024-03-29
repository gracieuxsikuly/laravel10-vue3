# Laravel avec Vue.js Application

Bienvenue dans l'application Laravel intégrant Vue.js !

## Description

Cette application combine la puissance du framework PHP Laravel avec la flexibilité du framework JavaScript Vue.js pour créer une application web robuste et réactive.

## Installation

1. **Clonage du dépôt :**

    ```
    git clone <url_du_depot>
    ```

2. **Installation des dépendances :**

    ```bash
    # Installation des dépendances Laravel
    composer install

    # Installation des dépendances Vue.js
    npm install
    ```

## Configuration

1. **Configuration de l'environnement :**

    - Créez une copie du fichier `.env.example` et renommez-la en `.env`.
    - Configurez les détails de votre base de données dans le fichier `.env`.

2. **Génération de la clé d'application :**

    ```
    php artisan key:generate
    ```

3. **Exécution des migrations :**

    ```
    php artisan migrate
    ```

## Lancement

1. **Serveur de développement :**

    ```bash
    php artisan serve
    ```

    L'application Laravel sera accessible à l'adresse `http://localhost:8000`.

2. **Compilation des assets Vue.js :**

    ```bash
    npm run dev
    ```

    Assurez-vous de compiler les assets Vue.js pour qu'ils soient accessibles dans l'application Laravel.

## Contribution

Les contributions sont les bienvenues! Si vous souhaitez contribuer à ce projet, veuillez créer une "Pull Request" avec vos modifications.

## Auteurs

- graciersikuly-
