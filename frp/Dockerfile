FROM alpine:3.6
ENV FRP_VERSION=frp_0.13.0_linux_amd64
RUN apk add --no-cache openssl \
  && wget https://github.com/fatedier/frp/releases/download/v0.13.0/$FRP_VERSION.tar.gz \
  && tar -xvf $FRP_VERSION.tar.gz 
WORKDIR /$FRP_VERSION
CMD ["./frps", "-c", "frps.ini"]

