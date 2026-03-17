<h1 align="center">Kollab</h1>

<p align="center">
Kollab est une plateforme collaborative de gestion de projets développée avec <strong>Laravel</strong>,  
reliée à une base de données <strong>MySQL</strong>, permettant aux équipes d'organiser  
et de suivre leurs projets selon une méthodologie <strong>Agile</strong> et <strong>Kanban</strong>.
</p>

<p align="center">
Le site intègre un système d'authentification sécurisé,<br>
un système de notification en temps réel,<br>
et propose une gestion hiérarchisée du travail : <strong>Sprints → Épics → Tâches</strong>.
</p>

<p>
Les visiteurs peuvent consulter la présentation du site.<br>
Les utilisateurs connectés peuvent créer des projets, gérer les collaborateurs, organiser le travail et visualiser l'avancement via un tableau Kanban et une roadmap.<br>
L’administrateur gère l’ensemble de la plateforme et peut modérer les utilisateurs et projets.
</p>

<h2>Actions à faire pour mettre en place le projet</h2>

<ul>
  <li>
    <strong>Cloner le dépôt :</strong><br>
    <pre><code>git clone https://github.com/DRINNHAUSENLou/Kollab.git
cd Kollab</code></pre>
  </li>

  <li>
    <strong>Installer les dépendances PHP et Node :</strong><br>
    <pre><code>composer install
npm install</code></pre>
  </li>

  <li>
    <strong>Créer le fichier .env et générer la clé de l’application :</strong><br>
    <pre><code>cp .env.example .env
php artisan key:generate</code></pre>
  </li>

  <li>
    <strong>Créer la base de données :</strong> <br>
    Créer une base nommée <strong>kollab</strong> dans phpMyAdmin ou via MySQL.
  </li>

  <li>
    <strong>Lancer les migrations et compiler les assets :</strong><br>
    <pre><code>php artisan migrate
npm run build</code></pre>
  </li>

  <li>
    <strong>Démarrer le serveur local :</strong><br>
    <pre><code>php artisan serve</code></pre>
  </li>

  <li>
    <strong>Accéder à l’application :</strong><br>
    <a href="http://localhost:8000">http://localhost:8000</a>
  </li>
</ul>

<h3 align="left">Langages et Outils :</h3>
<p align="left">
  <a href="https://laravel.com" target="_blank" rel="noreferrer">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/laravel/laravel-plain-wordmark.png" alt="laravel" width="40" height="40"/>
  </a>
  <a href="https://www.php.net" target="_blank" rel="noreferrer">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.png" alt="php" width="40" height="40"/>
  </a>
  <a href="https://www.mysql.com/" target="_blank" rel="noreferrer">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original-wordmark.png" alt="mysql" width="40" height="40"/>
  </a>
  <a href="https://vuejs.org/" target="_blank" rel="noreferrer">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vuejs/vuejs-original-wordmark.png" alt="vuejs" width="40" height="40"/>
  </a>
  <a href="https://tailwindcss.com/" target="_blank" rel="noreferrer">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-plain.png" alt="tailwindcss" width="40" height="40"/>
  </a>
  <a href="https://www.javascript.com/" target="_blank" rel="noreferrer">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.png" alt="javascript" width="40" height="40"/>
  </a>
</p>


