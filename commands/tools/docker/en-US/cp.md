+++
summary = "在容器与本机之间复制文件或目录。"
+++
---

## Purpose

Copy files or directories between a container and the local filesystem.

## Basic syntax

```bash
docker cp [OPTIONS] SRC_PATH DEST_PATH
```

## Common options

- `-a`: Preserve source UID/GID when possible.
- `-L`: Follow symbolic links in the source path.

## Common examples

```bash
docker cp ./config.yml web:/app/config.yml
docker cp web:/var/log/app.log .
```

## More options

This page covers selected high-frequency, practical options only. For the complete option list and details, see the [official Docker CLI documentation](https://docs.docker.com/reference/cli/docker/cp/).
