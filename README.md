# Kong-Docker

## Start

```
$ docker-compose up -d kong-database
$ docker-compose up -d --build
```

## Down

```
$ docker-compose down
```

### kong-database

- Listening port `5432`

### kong-gateway

- Listening port `8000`, `8001`, `8443`, `8443`

### kong-admin

- Listening port `1337`


