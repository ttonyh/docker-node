# alpine




#### Updates to the latest version of NPM and installs PM2

```
docker build -t ttonyh/node:<NODE_VERSION>-alpine-3.10.3 --build-arg version=<NODE_VERSION> .
docker push ttonyh/node:<NODE_VERSION>-alpine-3.10.3

```



```
docker build -t ttonyh/node:<VERSION>-alpine .
docker push ttonyh/node:<VERSION>-alpine
```



```
docker build -t ttonyh/node:<VERSION>-alpine . \
&& docker push ttonyh/node:<VERSION>-alpine
```

