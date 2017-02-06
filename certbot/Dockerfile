FROM alpine:3.5
MAINTAINER Nikita Volodin <me@qlonik.io>

EXPOSE 80 443
VOLUME /etc/letsencrypt /var/log/letsencrypt /varlib/letsencrypt

RUN apk add --no-cache certbot
ENTRYPOINT ["/usr/bin/certbot"]

