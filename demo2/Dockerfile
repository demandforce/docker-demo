FROM debian:jessie

MAINTAINER Consumer Team <DF_Consumer_Team@intuit.com>

RUN apt-get update && apt-get install -y nginx

ADD nginx.conf /etc/nginx/nginx.conf
ADD sites-available/default /etc/nginx/sites-available/default
ADD html /usr/share/nginx/html

EXPOSE 80

CMD ["-c", "/etc/nginx/nginx.conf"]
ENTRYPOINT ["/usr/sbin/nginx"]
