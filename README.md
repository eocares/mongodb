Realizado mediando el video https://www.youtube.com/watch?v=1s3Lu1rOrOE


docker hub mongodb: https://hub.docker.com/_/mongo

Coficacion del archivo docker-compose.yml
version: '3'

services:
some-mongo:
image: mongo
container_name: container_mongo
environment:

MONGO_INITDB_ROOT_USERNAME: admin
MONGO_INITDB_ROOT_PASSWORD: root
ports:
"27017:27017"
