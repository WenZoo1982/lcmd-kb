+++
summary = "将容器当前文件系统状态保存为新镜像。"
+++
---

## Purpose

Create a new image from a container's current filesystem changes.

## Basic syntax

```bash
docker commit [OPTIONS] CONTAINER [REPOSITORY[:TAG]]
```

## Common options

- `-a author`: Set the image author.
- `-m message`: Add a commit message.
- `-p`: Pause the container during commit.

## Common examples

```bash
docker commit web myapp:snapshot
docker commit -m "before upgrade" web myapp:backup
```

## More options

This page covers selected high-frequency, practical options only. For the complete option list and details, see the [official Docker CLI documentation](https://docs.docker.com/reference/cli/docker/commit/).
