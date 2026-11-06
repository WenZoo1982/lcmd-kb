+++
summary = "根据 Dockerfile 构建镜像。"
+++
---

## Purpose

Build an image from a Dockerfile and build context.

## Basic syntax

```bash
docker build [OPTIONS] PATH
```

## Common options

- `-t name:tag`: Name and tag the image.
- `-f file`: Select the Dockerfile.
- `--no-cache`: Disable build cache.
- `--pull`: Always attempt to pull newer base images.
- `--build-arg name=value`: Pass a build-time argument.
- `--platform platform`: Set the target platform.

## Common examples

```bash
docker build -t myapp:1.0 .
docker build -f docker/Dockerfile -t myapp .
docker build --no-cache -t myapp:debug .
```

## More options

This page covers selected high-frequency, practical options only. For the complete option list and details, see the [official Docker CLI documentation](https://docs.docker.com/reference/cli/docker/build/).
