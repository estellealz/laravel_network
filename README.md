# Réseau Social Laravel – Devoir de cours

Ce projet est un réseau social développé avec le framework Laravel dans le cadre d’un devoir de cours. Il permet de tester les fonctionnalités principales d’une application sociale en local.

## Installation du projet

1. Cloner le dépôt :

   git clone https://github.com/estellealz/laravel_network.git
   cd votre-repo

2. Installer les dépendances avec Composer :

   composer install

3. Copier le fichier .env.example en .env :

   cp .env.example .env

4. Configurer le fichier .env avec vos informations. Exemple :

   APP_NAME=Laravel
   APP_ENV=local
   APP_KEY=
   APP_DEBUG=true
   APP_URL=http://localhost

   DB_CONNECTION=mysql
   DB_HOST=127.0.0.1
   DB_PORT=3306
   DB_DATABASE=laravel_social
   DB_USERNAME=root
   DB_PASSWORD=

5. Créer la base de données "laravel_social" dans votre outil MySQL/MariaDB.

6. Générer la clé de l'application :

   php artisan key:generate

7. Lancer les commandes suivantes :

   php artisan storage:link
   php artisan optimize:clear
   php artisan serve

8. Accéder à l'application à l'adresse suivante :

   http://localhost:8000

## Remarques

- Ce projet a été réalisé dans un but pédagogique.
- Il est destiné à être utilisé localement pour démonstration.
- Aucun contenu n’est préchargé, vous pouvez créer un compte utilisateur et tester les fonctionnalités.
