# Appweb-flask-docker
Application created with Flask, along with Docker configurations * Dockerfile * to create a container

Features:
  - Alpine was used as the base of the image
  - The Dockerfile have dependencies for python and commands to start the applications.
### Create Image

```sh
$ docker build -t flaskapp .                                                
```

## Run Images
```sh
$ docker run -it --publish 7000:4000 -d flaskapp                                                 
```
