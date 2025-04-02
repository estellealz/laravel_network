<body style="font-family: Arial, sans-serif; line-height: 1.6; color: #333; max-width: 900px; margin: auto;">

  <h1 style="text-align: center; font-size: 2.8em; color: #480E33;">🌐 Réseau Social Laravel – Devoir de cours</h1>

  <p style="font-size: 1.2em; text-align: center;">
    Ce projet est un réseau social développé avec le framework Laravel dans le cadre d’un devoir de cours.<br>
    Il permet de tester les fonctionnalités principales d’une application sociale en local.
  </p>

  <hr>

  <h2 style="color: #480E33;">⚙️ Installation du projet</h2>

  <h3>1. Cloner le dépôt</h3>
  <pre><code>git clone https://github.com/votre-utilisateur/votre-repo.git
cd votre-repo</code></pre>

  <h3>2. Installer les dépendances avec Composer</h3>
  <pre><code>composer install</code></pre>

  <h3>3. Copier le fichier .env.example en .env</h3>
  <pre><code>cp .env.example .env</code></pre>

  <h3>4. Configurer le fichier <code>.env</code> avec vos informations</h3>
  <pre><code>APP_NAME=Laravel
APP_ENV=local
APP_KEY=
APP_DEBUG=true
APP_URL=http://localhost

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=[nom de votre base]
DB_USERNAME=[nom d'utilisateur de votre base]
DB_PASSWORD=[mot de passe de votre base]</code></pre>

  <h3>5. Créer la base de données</h3>
  <p>Créez la base de données nommée <code>[nom de votre base]</code> dans votre outil MySQL/MariaDB.</p>

  <h3>6. Générer la clé de l'application</h3>
  <pre><code>php artisan key:generate</code></pre>

  <h3>7. Lancer les commandes suivantes</h3>
  <pre><code>php artisan storage:link
php artisan optimize:clear
php artisan serve</code></pre>

  <h3>8. Accéder à l'application</h3>
  <p>L'application sera accessible à l'adresse suivante :</p>
  <p><strong>👉 <a href="http://localhost:8000" target="_blank">http://localhost:8000</a></strong> (ou autre selon votre URL locale)</p>

  <hr>

  <h2 style="color: #480E33;">📌 Remarques</h2>
  <ul>
    <li>Ce projet a été réalisé dans un but pédagogique.</li>
    <li>Il est destiné à être utilisé localement pour démonstration.</li>
    <li>Aucun contenu n’est préchargé, vous pouvez créer un compte utilisateur et tester les fonctionnalités.</li>
  </ul>

</body>
