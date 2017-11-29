#
# Dockerfile for python2
#

FROM alpine
MAINTAINER Bruno Cardoso Cantisano <bruno.cantisano@gmail.com>

RUN set -xe \
    && apk add --no-cache curl python \
    && curl -sSL https://bootstrap.pypa.io/get-pip.py | python

CMD ["python"]
