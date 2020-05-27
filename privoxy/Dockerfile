FROM alpine:3.10.3
MAINTAINER sean8694@gmail.com
RUN apk --no-cache --update add privoxy
VOLUME /etc/privoxy
CMD [ "privoxy", "--no-daemon", "/etc/privoxy/conf" ]
