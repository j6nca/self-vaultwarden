# self-vaultwarden
setup for self-hosting vaultwarden
## Setup
```
# vaultwarden setup
sudo docker pull vaultwarden/server:latest
mkdir vw-data
chmod go-rwx vw-data

# caddy setup
mkdir caddy
chmod go-rwx caddy
sudo docker pull caddy:2

# docker compose commands
## start
docker compose up -d
## stop
docker compose down
## restart
docker compose restart $SERVICE
```