.PHONY: image bash

IMAGE=oteet/memcached

image:
	docker build -t $(IMAGE) .

bash:
	docker run -ti $(IMAGE) /bin/bash

