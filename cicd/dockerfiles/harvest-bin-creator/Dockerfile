FROM golang:1.20.10-alpine

RUN apk add --no-cache bash git alpine-sdk

COPY entrypoint.sh /
RUN chmod +x /entrypoint.sh

ENTRYPOINT ["/entrypoint.sh"]
CMD [ "-h" ]


