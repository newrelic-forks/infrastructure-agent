FROM alpine:3.18.4

RUN apk --update add bash curl jq zip libarchive-tools;

ADD entrypoint.sh /
RUN chmod +x /entrypoint.sh

CMD ["/entrypoint.sh"]
