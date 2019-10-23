# docker-node
Unofficial Docker Image for Node.js

#### Updates to the latest version of NPM and installs PM2

```
docker build -t ttonyh/node:<NODE_VERSION>-alpine-3.10.2 --build-arg version=<NODE_VERSION> .
docker push ttonyh/node:<NODE_VERSION>-alpine-3.10.2

```