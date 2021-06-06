# Create image and container

Create a docker image inside a folder where a `Dockerfile` exists.

```
docker build -t [image-name]:[tagname] .
```

Create a docker container from an image

```
docker create --name [container-name] -p [host-port]:[container-port] [image-name]:[tagname]
```

Create a docker container from an image with environment variable

```
docker create --name [container-name] -p [host-port]:[container-port] -e [env-variable]=[value] [image-name]:[tagname]
```

Start a container

```
docker start [container-name]
```