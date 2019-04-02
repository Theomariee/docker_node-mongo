# Docker Node MongoDB Example

> Simple example of a dockerized Node/Mongo app

## Quick Start

```bash
# Run in Docker
docker-compose up
# use -d flag to run in background

# Tear down
docker-compose down

# To be able to edit files, add volume to compose file
volumes: ['./:/usr/src/app']

# To re-build
docker-compose build

# docker_node-mongo

Pour installer docker-compose :

`sudo curl -L "https://github.com/docker/compose/releases/download/1.24.0/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose`

puis

`sudo chmod +x /usr/local/bin/docker-compose`

Pour composer et run l'image, se placer dans le dossier où se trouver le fichier docker-compose.yml :

`docker-compose up`

Tester l'application sur le localhost.
