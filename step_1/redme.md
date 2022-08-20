## Introduction
Basics Comands of docker

## Commands
- docker build -t web:v1 // Build Image
- docker container run -d --name container-1 -p 8080:80 // run container
- docker ps // container progress
- docker ps -a // Container progress all
- docker exec -ti container-1 /bin/bash
- docker container stop container-1 // Kill Container
- docker container rm container-1 // remove container
- docker container rm container-1 -f // remove and stop container
- docker images // show images
- docker ls // show images
- docker image rm image-name:v1 // remove image from container

## Notes
- We can't delete container directly it needs to be stopped first or remove forcefully
