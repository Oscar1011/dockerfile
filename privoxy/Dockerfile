FROM centos
MAINTAINER sean8694@gmail.com
RUN yum install -y epel-release && yum install -y privoxy
ADD privoxy_cfg.conf /
ADD entrypoint.sh /
CMD ["./entrypoint.sh"]