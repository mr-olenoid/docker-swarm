# docker-swarm
Bunch of yamls to help with docker swarm deployments.

# traefik.yaml
Create shared network first
docker network create --driver=overlay traefik-public
