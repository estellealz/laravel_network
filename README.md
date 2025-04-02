# Réseau Social Laravel – Devoir de cours

Ce projet est un réseau social développé avec le framework Laravel dans le cadre d’un devoir de cours. Il permet de tester les fonctionnalités principales d’une application sociale en local.

## Installation du projet

1. Cloner le dépôt :

   git clone https://github.com/votre-utilisateur/votre-repo.git
   cd votre-repo

2. Installer les dépendances avec Composer :

   composer install

3. Copier le fichier .env.example en .env :

   cp .env.example .env

4. Configurer le fichier .env avec vos informations. Exemple :

   APP_NAME=Laravel <br>
   APP_ENV=local <br>
   APP_KEY= <br>
   APP_DEBUG=true <br>
   APP_URL=http://localhost <br>
<br>
   DB_CONNECTION=mysql <br>
   DB_HOST=127.0.0.1 <br>
   DB_PORT=3306 <br>
   DB_DATABASE= [nom de votre base] <br>
   DB_USERNAME= [om d'utilisateur de votre base] <br>
   DB_PASSWORD= [mot de passe de votre base] <br>

5. Créer la base de données "[nom de votre base]" dans votre outil MySQL/MariaDB.

6. Générer la clé de l'application :

   php artisan key:generate

7. Lancer les commandes suivantes :

   php artisan storage:link
   php artisan optimize:clear
   php artisan serve

8. Accéder à l'application à l'adresse suivante :

   http://localhost:8000 [ou autre en fonction de votre url local]

## Remarques

- Ce projet a été réalisé dans un but pédagogique.
- Il est destiné à être utilisé localement pour démonstration.
- Aucun contenu n’est préchargé, vous pouvez créer un compte utilisateur et tester les fonctionnalités.
