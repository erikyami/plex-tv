## Configuração Plex Server

Configurar um servidor Plex utilizando docker / docker-compose

Plex: https://www.plex.tv/


Base utilizada: https://hub.docker.com/r/linuxserver/plex
GitHub: https://github.com/linuxserver/docker-plex

PLEX um media server


Tecnologia: Docker

## Configuração

Criar os diretórios:

```bash
sudo mkdir -p /mnt/plex/{config,movies,tvseries}

sudo chown $USER:USER -R /mnt/plex
```

## Docker-Compose

```bash
docker compose up -d
```

## Acessar
Acessar o navegador: http://localhost:32400/
