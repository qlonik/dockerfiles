FROM alpine:3.5
MAINTAINER Nikita Volodin <me@qlonik.io>

EXPOSE 80 443
VOLUME /etc/letsencrypt /var/log/letsencrypt /var/lib/letsencrypt

RUN apk add --no-cache certbot
ENTRYPOINT ["/usr/bin/certbot"]

