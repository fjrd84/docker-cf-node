# docker-cf-node

Docker image based in node v8.9.4 where the CloudFoundry CLI is preinstalled.

## Build and start locally

Build this image locally and name it `cf_node:8.9.4`:

`docker build -t "cf_node:8.9.4" .`

Start the just built image and attatch a terminal:

`docker run -ti cf_node:8.9.4 /bin/bash`
