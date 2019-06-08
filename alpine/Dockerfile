FROM alpine
MAINTAINER Antonio Novaes - antonionovaesjr@gmail.com
RUN apk --update --no-cache add net-tools sed bash iproute2 curl wget vim lsof pstree htop shadow iputils lynx tzdata && \ 
cp /usr/share/zoneinfo/America/Bahia /etc/timezone 
ENV TZ /usr/share/zoneinfo/America/Bahia
ENV LANG C.UTF-8
