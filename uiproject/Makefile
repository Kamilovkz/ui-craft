.PHONY: all
all: up

.PHONY: build
build:
	docker build --tag python-django .

.PHONY: up
up: build
	docker run --publish 8000:8000 python-django