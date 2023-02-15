# Docker+NodeJS+RPI

Test Web App dockerized into a RPI.

## Getting Started

```
docker build . -t robomucca/docker-node-rpi
```
```
docker run -p 80:8080 -d robomucca/docker-node-rpi
```

## Useful Commands

Action  | Command
------------- | -------------
List images  | ```docker images```
Delete image  | ```docker rmi -f <image ID>```
List running containers | ```docker ps```
Delete container | ```docker kill <container ID>```
