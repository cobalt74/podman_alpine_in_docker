# podman_alpine_in_docker

[![Docker Image CI](https://github.com/cobalt74/podman_alpine_in_docker/actions/workflows/docker-image.yml/badge.svg)](https://github.com/cobalt74/podman_alpine_in_docker/actions/workflows/docker-image.yml)

Docker image with podman rootless based to Alpine 

## Build

```shell
docker build -t alpine-podman-rootless .
```

## Run

```shell
docker run -it --rm --privileged alpine-podman-rootless podman run alpine:latest echo "launch Alpine image by Podman in Docker !"
```


@Cobalt74
