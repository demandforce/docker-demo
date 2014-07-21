FROM nginx

MAINTAINER Consumer Team <DF_Consumer_Team@intuit.com>

ADD nginx.conf /etc/nginx.conf
ADD sites-available/default /etc/nginx/sites-enabled/default
ADD html /usr/local/nginx/html

EXPOSE 80

CMD ["-c", "/etc/nginx.conf"]
ENTRYPOINT ["/usr/local/sbin/nginx"]
