# CMS Minecraft sous Docker

Environnement de test pour les CMS Minecraft les plus communs.

## Instructions

1. Copier l'installation de TrixCMS dans le dossier `trixcms/www`
2. Modifier la variable `VIRTUAL_HOST` de chaque service dans le docker-compose.
3. Modifier son `/etc/hosts` en conséquence
4. TrixCMS : modifier les droits sur les fichiers pour l'installation avec `sudo chmod www-data:www-data -R www/<dossier>`
5. `docker-compose up`


# MySQL
hôte: mysql
base de données: <nom du service>
user: mysql
password: mysql

