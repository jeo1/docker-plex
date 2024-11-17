### .env
```.env
COMPOSE_PROJECT_NAME=plex
TIMEZONE=America/Toronto

DOCKER_NETWORK=<name of docker network>
IP_ADDRESS=<ip address of container>

# Update
SONARR=<path to sonarr media>
RADARR=<path to radarr media>
OTHER=<path to other media>
OTHER_QBITTORRENT=<path to qbittorrent media>

PLEX_CONFIG=<path to plex config>

```

### private/.env
```.env
PLEX_CLAIM=<private plex token>
```
- Can obtain a claim token from https://plex.tv/claim and input here. Keep in mind that the claim tokens expire within 4 minutes.