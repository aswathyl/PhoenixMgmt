## PRMS


## Prerequisits:

* Docker
* Docker-compose

## Running

```
docker-compose up --build ## First time
```

Build scripts will take care of deploying application and mysql containers and database table creation.

## FAQ

Sometimes you may get table already exists when starting the container.

```
docker-compose kill
docker-compose rm
docker-compose up
```