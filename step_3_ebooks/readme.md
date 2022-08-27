## Introduction
Basics Comands of docker

## Commands
- docker run -d --name c1 -p 8080:80 -v "$(pwd)/":/usr/share/nginx/html web:v1
    - v = volume mounting
    - "$(pwd)/" = path of current dir which is in you system
    - :/ebook = mapping container path(this path is inside of the container) 
- docker login // make sure to login first
- docker image tag web:v1 hamzah/web:v1 // change tag for deployement
- docker push hamzah/web:v1


## Resources
https://docs.google.com/presentation/d/1wk0JTNvxLu2sn7Ua8mQvO6yuzE1wEjrBmDMgzkfDVUk/edit