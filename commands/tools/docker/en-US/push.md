+++
summary = "将本机镜像推送到镜像仓库。"
+++
---

## Purpose

Upload an image to a registry.

## Basic syntax

```bash
docker push [OPTIONS] IMAGE[:TAG]
```

## Common options

- `-a`: Push all tagged images in the repository.
- `-q`: Suppress progress output.

## Common examples

```bash
docker tag myapp:1.0 username/myapp:1.0
docker push username/myapp:1.0
```

## More options

This page covers selected high-frequency, practical options only. For the complete option list and details, see the [official Docker CLI documentation](https://docs.docker.com/reference/cli/docker/push/).
