FROM alpine:3.8

RUN apk -U add --no-cache py-pip

RUN pip install shadowsocks 

VOLUME /ssserver
WORKDIR /ssserver

ENTRYPOINT ["ssserver"]