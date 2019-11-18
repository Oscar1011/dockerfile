FROM alpine:3.10.3
MAINTAINER sean8694@gmail.com
RUN apk --no-cache --update add privoxy
ADD privoxy_cfg.conf /
ADD entrypoint.sh /
CMD ["sh", "/entrypoint.sh"]