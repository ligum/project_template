FROM alpine
RUN apk add --no-cache python3
RUN apk add --no-cache curl wget busybox-extras netcat-openbsd python3 py-pip
RUN apk add --no-cache py3-numpy
#RUN pip install numpy
RUN apk --purge -v del py-pip
CMD tail -f /dev/null
