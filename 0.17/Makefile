.PHONY: all build push

TAG ?= noahhuppert/factorio:0.17.79
CONTAINER_CLI ?= sudo podman

all: build push

build:
	${CONTAINER_CLI} build -t "${TAG}" .

push:
	${CONTAINER_CLI} push "${TAG}"
