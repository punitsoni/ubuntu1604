# ubuntu1604 [![Docker Build Statu](https://img.shields.io/docker/build/punitsoni/ubuntu1604.svg)](https://hub.docker.com/r/punitsoni/ubuntu1604/builds/)
Dockerfile for an interactive ubuntu setup
```
docker pull punitsoni/ubuntu1604
```

## Build and run container from Dockerfile

Build image from Dockerfile
```
docker build -t punits-ubuntu:latest .
```

Create container based on image
```
docker run -it --hostname punits-ubuntu --name punits-ubuntu punits-ubuntu
```

Start an existing container
```
docker start -i -a punits-ubuntu
```
