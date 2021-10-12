# Docker Setup List 

### List of Services
* Backend Todo API Server
* MongoDB 
* Frontend Todo VueJS App

## Command List 
* Development

```bash

docker-compose  -f .\docker-compose.yml -f .\docker-compose-dev.yml up --build -d #inital build container and run in detach mode

docker-compose  -f .\docker-compose.yml -f .\docker-compose-dev.yml up -d # run in detach mode

docker-compose  -f .\docker-compose.yml -f .\docker-compose-dev.yml down -v #kill runing instance

```

* Production

```bash

docker-compose  -f .\docker-compose.yml -f .\docker-compose-prod.yml up --build -d #inital build container and run in detach mode

docker-compose  -f .\docker-compose.yml -f .\docker-compose-prod.yml up -d # run in detach mode

docker-compose  -f .\docker-compose.yml -f .\docker-compose-prod.yml down -v #kill runing instance

```

## Reference Links