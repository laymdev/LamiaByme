# LamiaByme

LamiaByme est un site internet présentant des peintures artistiques. But it s not me.

## Environnement de développement

## Pré-requis

* PHP 7.4
* Composer
* Symfony CLI
* Docker
* Docker-compose

Vous pouvez vérifier les pré-requis (sauf Docker et Docker) avec la commande suivante (de la CLI Symfony) :

```blash
symfony check:requirements
```

### Lancer l'environnement de développement

```bash

docker-compose up -d
symfony serve -d
```

## Lancer des tests

```bash
php bin/phpuit --testdox