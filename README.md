# Notebooks and python packages to get data from ES and predict vendor through ML model
This repository is composed of :
- certs dir : cert to encrypt connection with ES node
- config dir : conf files (for ES connetion)
- data dir : with raw binary big data
- libs dir : collection of custom python packages
- scripts dir : a script for intializing Docker image
- work dir : colection of notebooks

docker-compose.yml : docker-compose conf file
Dockerfile : docker conf file for image creation

## Create docker image

```bash
docker-compose build --no-cache
```

# #partexp2 Sycomore-tech

## Run image  in container

```bash
docker-compose up
```

## Connect to notebook

Through web browser go to http://localhost:8888 (or any port you filled in)
