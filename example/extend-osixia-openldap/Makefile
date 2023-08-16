NAME = kaver79/extend-openldap
VERSION = 0.1.1

.PHONY: all build build-nocache

all: build push

build:
	docker build -t $(NAME):$(VERSION) --rm .

build-nocache:
	docker build -t $(NAME):$(VERSION) --no-cache --rm .

push:
	docker push $(NAME):$(VERSION)
