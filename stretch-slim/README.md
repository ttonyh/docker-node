# stretch-slim



#### Updates to the latest version of NPM and installs PM2

```
docker build -t ttonyh/node:<NODE_VERSION>-stretch-slim --build-arg version=<NODE_VERSION> .
docker push ttonyh/node:<NODE_VERSION>-stretch-slim

```


```
docker build -t ttonyh/node:<VERSION>-stretch-slim .
docker push ttonyh/node:<VERSION>-stretch-slim
```



```
docker build -t ttonyh/node:<VERSION>-stretch-slim . \
&& docker push ttonyh/node:<VERSION>-stretch-slim
```

