# traefik-example

## Description

Base pour le déploiement de Traefik en mode Docker, sans exploitation du tableau de bord.

## Installation

1. Copier le fichier `.env.example` en `.env` puis remplir les variables.
2. Renseigner son courriel (champ `email`) dans le fichier `data/traefik/conf/traefik.yaml`
3. Adapter si nécessaire les entêtes HTTP dans `data/traefik/conf/headers.yaml`
4. Compléter le fichier `docker-compose.yaml` en s'appuyant sur l'exemple
5. `docker compose up -d`
