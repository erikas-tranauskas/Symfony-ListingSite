# Symfony ListingSite
Assignment for job interview:
Create a simple CRUD listing site using Symfony framework.
Dockerized.

Registered and signed in users can create and edit their own listing posts.

# Installation
1. composer install
2. php bin/console doctrine:migrations:diff
3. php bin/console doctrine:migrations:migrate

Run 'docker-compose build' and 'docker-compose up' if running on Docker.

symfony_dev.sql file added if needed.
