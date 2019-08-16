# docker-node
Unofficial Docker Image for Node.js


```
export NODE_VERSION=12.8.1
export ALPINE_VERSION=3.10.1

docker build -t ttonyh/node:$NODE_VERSION-alpine-$ALPINE_VERSION .
docker push ttonyh/node:$NODE_VERSION-alpine-$ALPINE_VERSION

```