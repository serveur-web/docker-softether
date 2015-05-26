# Docker image for SoftEther VPN

This will deploy a fully functional [SoftEther VPN](https://www.softether.org) server as a docker image.

Available on [Docker Hub](https://registry.hub.docker.com/u/frosquin/softether/).

## Download

    docker pull frosquin/softether

## Run


Simplest version:

    touch /etc/vpnserver/vpn_server.config
    docker run -d -v /etc/vpnserver/vpn_server.config:/usr/local/vpnserver/vpn_server.config --net host --name softether frosquin/softether

