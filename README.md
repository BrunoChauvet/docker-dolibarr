
# Build a docker image
$ sudo docker build -t "dolibarr" docker/

# Run an image in a container
$ sudo docker run -t -i --name=dolibarr_container dolibarr /bin/bash