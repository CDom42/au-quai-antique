# au-quai-antique

Ceci est le readme du site Web du restaurant au-quai-antique, proposant une expérience gastronomique sans artifices.

## Environnement de développement

### Pré-requis

-   PHP 8.1
-   Composer
-   Symfony CLI
-   Docker
-   Docker-compose

Vous pouvez vérifier les pré-requis (sauf Docker et Docker-compose) avec la commande suivante (de la CLI Symfony) :

```bash
symfony check:requirements
```

### Lancer l'environnement de développement

```bash
docker-compose up -d
symfony serve -d
```
