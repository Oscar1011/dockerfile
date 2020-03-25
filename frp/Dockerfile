FROM alpine:3.11.5
ENV FRP_VERSION=0.32.0
RUN apk add --no-cache openssl \
  && wget https://github.com/fatedier/frp/releases/download/v${FRP_VERSION}/frp_${FRP_VERSION}_linux_amd64.tar.gz \
  && tar -xvf frp_${FRP_VERSION}_linux_amd64.tar.gz \
  && mv frp_${FRP_VERSION}_linux_amd64 frp_linux_amd64
WORKDIR /frp_linux_amd64
CMD ["./frps", "-c", "frps.ini"]
