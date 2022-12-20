# Just a bunch of services:
## - jackett port 9117
## - qbittorrent port 8068 (login:admin, pwd:adminadmin)
## - sonarr port 8989
## - radarr port 7878
---
## How start for debug
``` bash
docker compose up
```

## Start as service
``` bash
docker compose up -d
```

## All the necessary folders will be created a level higher from the .yml file.