# Docker Cheat Sheet

This is a simple list of useful docker commands. 
This is both for my reference and for anyone else looking for a quick refresher.

* docker version - Show the Docker version information
* docker-compose version - Show the Docker-compose version information
* docker info - Display system-wide information
* docker login

---

* docker image ls - List images
* docker image pull
* docker image history
* docker image inspect
* docker image tag
* docker image push
* docker image build

---

* docker container ls - List containers
* docker container run - Run a command in a new container
ex: docker container run - publish 80:80 - detach - name webhost nginx
ex: docker container run -d - name mysql -e MYSQL_RANDOM_ROOT_PASSWORD=true mysql
ex: docker container run -it - name proxy nginx bash

* docker container logs - Fetch the logs of a container
* docker container top - Display the running processes of a container
* docker container rm - Remove one or more containers
* docker container stop - Stop one or more running containers
* docker container start - Start one or more stopped containers
* docker container inspect - Display detailed information on one or more containers
* docker container stats - Display a live stream of container(s) resource usage statistics
* docker container exec - Run a command in a running container
* docker container port - List port mappings or a specific mapping for the container

---

* docker network ls
* docker network inspect
* docker network create
* docker network connect

---

* docker volume ls
* docker volume inspect
