.PHONY: all build push

TAG ?= noahhuppert/factorio:0.17.14

all: build push

build:
	docker build -t "${TAG}" .

push:
	docker push "${TAG}"
