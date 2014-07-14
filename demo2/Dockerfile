FROM nginx

MAINTAINER Consumer Team <DF_Consumer_Team@intuit.com>

ADD html /usr/share/nginx/html
ADD nginx.conf /etc/nginx/nginx.conf

EXPOSE 80

CMD ["-c", "/etc/nginx/nginx.conf"]
ENTRYPOINT ["/usr/sbin/nginx"]
