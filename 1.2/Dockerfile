FROM influxdb:1.2.0-alpine

RUN apk update && apk add curl python ca-certificates && rm -rf /var/cache/apk/*

RUN cd /usr/local/bin; curl https://storage.googleapis.com/pub/gsutil.tar.gz| tar xfz -
