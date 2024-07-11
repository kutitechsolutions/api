# Docker build usage:
# 	docker build . -t sodafoundation/apiserver:latest
# Docker run usage:
# 	docker run -d --net=host -v /etc/opensds:/etc/opensds sodafoundation/apiserver:latest

FROM ubuntu:xenial-20201014

COPY osdsapiserver /usr/bin

# Define default command.
CMD ["/usr/bin/osdsapiserver"]
