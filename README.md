# docker-cf-node

Docker image based in node v8.9.4 where the CloudFoundry CLI is preinstalled.

## Image on Docker Hub

This image is available on Docker Hub on the following URL: [https://hub.docker.com/r/jdonado/docker-cf-node/](https://hub.docker.com/r/jdonado/docker-cf-node/).

## Build and start locally

Build this image locally and name it `cf_node:8.9.4`:

`docker build -t "cf_node:8.9.4" .`

Start the just built image and attatch a terminal:

`docker run -ti cf_node:8.9.4 /bin/bash`
