REPO_NAME ?= wagnermanganelli164
IMAGE_NAME = $(REPO_NAME)/webserver-hello-world
TAG = latest

build-image:
	docker build -t $(IMAGE_NAME):$(TAG) .

push-image:
	docker push $(IMAGE_NAME):$(TAG)

.PHONY: build-image push-image