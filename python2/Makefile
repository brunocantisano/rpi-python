.PHONY: all build push test 

DOCKER_IMAGE_NAME=paperinik/rpi-python

all: build

build:
	docker build -t $(DOCKER_IMAGE_NAME):v2 .

push:
	docker push $(DOCKER_IMAGE_NAME)

test:
	docker run --rm $(DOCKER_IMAGE_NAME) /bin/echo "Success."
