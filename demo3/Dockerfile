FROM nginx

MAINTAINER Consumer Team <DF_Consumer_Team@intuit.com>

ADD html /usr/local/nginx/html
ADD nginx.conf /etc/nginx.conf
ADD sites-available/default /etc/nginx/sites-enabled/default

EXPOSE 80

CMD ["-c", "/etc/nginx.conf"]
ENTRYPOINT ["/usr/local/sbin/nginx"]
