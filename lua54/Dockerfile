FROM alpine:latest

RUN apk add --no-cache lua5.4

RUN ln -s /usr/bin/lua5.4 /usr/bin/lua

WORKDIR /scripts

CMD ["lua"]
