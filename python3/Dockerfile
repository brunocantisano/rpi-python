#
# Dockerfile for python3
#

FROM alpine
MAINTAINER Bruno Cardoso Cantisano <bruno.cantisano@gmail.com>

RUN set -xe \
    && apk add --no-cache curl python3 \
    && curl -sSL https://bootstrap.pypa.io/get-pip.py | python3

CMD ["python3"]
