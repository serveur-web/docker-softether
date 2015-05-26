# Docker image for SoftEther VPN

This will deploy a fully functional [SoftEther VPN](https://www.softether.org) server as a docker image.

Available on [Docker Hub](https://registry.hub.docker.com/u/serveurweb/docker-se/).

## Download

    docker pull serveurweb/docker-se

## Run


Simplest version:

    docker run -d --net host --name softether serveurweb/docker-se
