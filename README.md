# simpleecdev
Simple docker compose stack for mysql, phpmyadmin and elasticsearch. Uses .env file to store sensitive information. In this case $mysql_pw which is the root password for mysql.

Includes:
* MySQL
* phpMyAdmin
* ElasticSearch
* Portainer (https://portainer.io)

# Usage
Clone the repo and run "docker-compose up -d". Services will be available on localhost:8080, localhost:3306 and localhost:9000.
