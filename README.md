# Desafio Docker - Primeiros Passos

## Desafio 01 - Banco de Dados PostgreSQL
```
docker container run -d -p 5432:5432 -e POSTGRES_DB=curso_docker -e POSTGRES_USER=docker_usr -e POSTGRES_PASSWORD=docker_pwd postgres
```

## Desafio 02 - Banco de Dados MySQL
```
docker container run -d -p 3306:3306 -e MYSQL_DATABASE=docker_db -e MYSQL_USER=docker_usr -e MYSQL_PASSWORD=docker_pwd -e MYSQL_ROOT_PASSWORD=dockeroot123 mysql
```

## Desafio 03 - Banco de Dados MongoDB
```
docker container run -d -p 27017:27017 -e MONGO_INITDB_ROOT_USERNAME=mongo_usr -e MONGO_INITDB_ROOT_PASSWORD=mongo_pwd mongo
```