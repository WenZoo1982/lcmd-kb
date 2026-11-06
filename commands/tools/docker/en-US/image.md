+++
summary = "管理 Docker 镜像。"
+++
---

## Purpose

Manage Docker images.

## Basic syntax

```bash
docker image COMMAND
```

## Common options

- `ls`: List images.
- `pull`: Pull an image.
- `push`: Push an image.
- `rm`: Remove images.
- `inspect`: Inspect an image.
- `prune`: Remove unused images.
- `tag`: Tag an image.
- `save` / `load`: Export or import image archives.

## Common examples

```bash
docker image ls
docker image pull nginx
docker image inspect nginx
docker image prune
docker image rm nginx
```

## More options

This page covers selected high-frequency, practical options only. For the complete option list and details, see the [official Docker CLI documentation](https://docs.docker.com/reference/cli/docker/image/).
