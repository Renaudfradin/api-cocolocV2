# api-cocolocV2

API du porjet cocoloc 

## Project Setup

Installer les dependences 

```sh
composer install
```

Lancer le docker 

```sh
docker compose up --build
```

Générer les clés publiques et priver de JWT

```sh
symfony console lexik:jwt:generate-keypair
```

### Compile for Development

```sh
symfony serve
```

run les migration avec:

```sh
php bin/console do:mi:mi
```

run les fixtures 

```sh
php bin/console doctrine:fixtures:load
```

Pour voir la page API PLATFORM : https://127.0.0.1:8000/api