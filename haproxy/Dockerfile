FROM haproxy:2.1.3

RUN groupadd haproxy && useradd haproxy -g haproxy

RUN mkdir -p /var/lib/haproxy/

COPY haproxy.cfg /usr/local/etc/haproxy/haproxy.cfg
EXPOSE 80

VOLUME /dev/log