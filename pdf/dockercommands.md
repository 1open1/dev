# Docker Commands Cheat Sheet

## Version
```bash
docker --version
```

## Run Container
```bash
docker run --name <name> -d -it <image>
```

## List Containers
```bash
docker containers ls
```

## Stop Container
```bash
docker container stop <container_id>
```

## Start Container
```bash
docker container start <container_id>
```

## Remove Container
```bash
docker container rm <container_id>
```

## List Images
```bash
docker images
```

## Remove Image
```bash
docker image rm <image_id>
```

## Build Image
```bash
docker build -t <tag> .
```

## Push Image
```bash
docker push <username>/myapp:latest
```

## Create Network
```bash
docker network create -d bridge <network_name>
```

## List Networks
```bash
docker network ls
```

## Create Volume
```bash
docker volume create
```

## Swarm Init
```bash
docker swarm init --advertise-addr <IP>
```

## Swarm Join
```bash
docker swarm join <token> <managerIP>
```

## Create Service
```bash
docker service create --name mynginx -d -p 80:8080 --replicas 3 nginx
```

## Inspect Service
```bash
docker service inspect mynginx
```

## List Services
```bash
docker service ls
```

## Scale Service
```bash
docker service scale mynginx=5
```

## Leave Swarm
```bash
docker swarm leave
```

## List Nodes
```bash
docker node ls
```
