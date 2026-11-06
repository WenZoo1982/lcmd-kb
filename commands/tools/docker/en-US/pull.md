+++
summary = "从镜像仓库下载镜像。"
+++
---

## Purpose

Download an image or repository from a registry.

## Basic syntax

```bash
docker pull [OPTIONS] IMAGE[:TAG|@DIGEST]
```

## Common options

- `-a`: Pull all tagged images in the repository.
- `--platform platform`: Select the target platform.
- `-q`: Suppress progress output.

## Common examples

```bash
docker pull nginx
docker pull nginx:alpine
docker pull --platform linux/arm64 nginx
```

## More options

This page covers selected high-frequency, practical options only. For the complete option list and details, see the [official Docker CLI documentation](https://docs.docker.com/reference/cli/docker/pull/).
