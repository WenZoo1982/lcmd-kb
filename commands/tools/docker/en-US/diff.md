+++
summary = "查看容器文件系统相对镜像的改动。"
+++
---

## Purpose

Inspect changes to a container's filesystem compared with its image.

## Basic syntax

```bash
docker diff CONTAINER
```

## Common options

- `A`: Added file or directory.
- `C`: Changed file or directory.
- `D`: Deleted file or directory.

## Common examples

```bash
docker diff web
```

## More options

This page covers selected high-frequency, practical options only. For the complete option list and details, see the [official Docker CLI documentation](https://docs.docker.com/reference/cli/docker/diff/).
