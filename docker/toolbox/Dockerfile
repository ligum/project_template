FROM alpine
RUN apk add --no-cache curl wget busybox-extras netcat-openbsd python py-pip bash && \
    pip install awscli
RUN apk add --no-cache python3
#RUN apk --purge -v del py-pip
CMD tail -f /dev/null
