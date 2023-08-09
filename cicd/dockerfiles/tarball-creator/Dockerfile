FROM alpine:3.16.7

RUN apk --update add bash curl jq zip libarchive-tools;

ADD entrypoint.sh /
RUN chmod +x /entrypoint.sh

CMD ["/entrypoint.sh"]
