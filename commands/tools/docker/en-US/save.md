+++
summary = "将一个或多个镜像保存为 tar 归档。"
+++
---

## Purpose

Save one or more images to a tar archive.

## Basic syntax

```bash
docker save [OPTIONS] IMAGE...
```

## Common options

- `-o file`: Write the archive to a file.

## Common examples

```bash
docker save -o images.tar nginx:latest myapp:1.0
docker save nginx:latest > nginx.tar
```

## More options

This page covers selected high-frequency, practical options only. For the complete option list and details, see the [official Docker CLI documentation](https://docs.docker.com/reference/cli/docker/save/).
