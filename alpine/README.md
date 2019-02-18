# Imagem Base do Alpine

```
FROM alpine
MAINTAINER Antonio Novaes - antonionovaesjr@gmail.com
RUN apk update && apk add net-tools sed bash iproute2 curl wget vim lsof pstree htop shadow iputils
```
