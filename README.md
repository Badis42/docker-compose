# DOCKER-COMPOSE
(I'm using [Docker Toolbox](https://www.docker.com/products/docker-toolbox))

```
docker-machine start default
docker-machine env default

docker-compose config
docker-compose up -d
docker-compose ps
docker-machine ip
```

Force rebuild
```
docker-compose up -d --build
```

Show log
 docker logs [container_name]
