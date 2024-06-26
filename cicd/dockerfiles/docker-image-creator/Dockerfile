FROM alpine:3.17

RUN apk --update add bash make curl docker

ADD entrypoint.sh /
RUN chmod +x /entrypoint.sh

CMD ["/entrypoint.sh"]
