FROM amd64/busybox

MAINTAINER admin@kubepnp.cloud

ADD kubepnp/index.html /www/index.html
EXPOSE 80
CMD httpd -p 80 -h /www; tail -f /dev/null
