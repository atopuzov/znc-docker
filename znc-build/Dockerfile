FROM alpine:3.3

RUN apk --no-cache add \
    znc \
    znc-modperl \
    znc-modtcl \
    znc-extra \
    ca-certificates

EXPOSE 6667

VOLUME /znc-data

CMD ["znc", "--foreground", "--datadir=/znc-data"]
