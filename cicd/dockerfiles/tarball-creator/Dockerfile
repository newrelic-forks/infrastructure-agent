FROM alpine:3.18.3

RUN apk --update add bash curl jq zip libarchive-tools;

ADD entrypoint.sh /
RUN chmod +x /entrypoint.sh

CMD ["/entrypoint.sh"]
