## tutoYoan

* PHP 7.4
* Composer
* Symfony CLI
* Docker
* Docker-compose

## Lancer l'environnement de développement

composer install
yarn install
yarn encore dev --watch
docker-compose up -d
symfony server:start -d

## Ajout des données de tests

symfony console doctrine:fixtures:load

## Lancer des tests

php bin/phpunit --testdox