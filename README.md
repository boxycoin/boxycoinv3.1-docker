# boxycoinv3.1-docker
Dockerfile to build BOXY Coin Wallet V3.1 in Ubuntu 16.04 Container

## DOCKER IMAGE hosted at [hub.docker.com](https://hub.docker.com/r/boyroywax/boxy-wallet-v3.1-ubuntu16.04)

## System Requirements
* Docker for Desktop (Mac OSX, WIN, linux)
* Or any other installation capable of building docker images.

## Features:
* Builds boxyd from source in Ubuntu 16.04 container.
* Removes unnecessary files to reduce image size (more could be done)
* Adds boxy.conf to /root/.boxy/
* Applies latest blockchain bootstrap to /root/.boxy/
* On startup the container runs boxyd -daemon and waits.

## Source Citation:
Code was adapted from [bostontrader github](https://github.com/bostontrader/crypto-docker)
