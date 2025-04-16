# PapaGateau :
Single page application pour PapaGateau (patissier à la Seyne sur mer).

# Installation :
- Installer MySQL
- Installer PHP
- Installer wamp

# Créer le projet Symfony :
- composer create-project symfony/skeleton:"7.0.*" PapaGateau
- composer require webapp -> dans le dossier du projet
- Pusher les modifications sur le repository Github :

# Créer un repository sur Github
- git config --global --add safe.directory D:/Symfony/PapaGateau pour ignorer tous les problèmes d’accès
- git add .
- git commit -m "Premier commit du projet Symfony PapaGateau"
- git branch -M main
- git push -u origin main
- git checkout -b nom-de-ta-branche pour créer une branche
- git push -u origin nom-de-ta-branche pour pusher sur la branche

# Démarrer le serveur :
- php -S localhost:8000 -t public

# Création des controllers :
- php bin/console make:controller -> HomeController
- php bin/console make:controller -> ProductController
