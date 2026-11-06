+++
summary = "删除一个或多个本机镜像。"
+++
---

## Purpose

Remove one or more local images.

## Basic syntax

```bash
docker rmi [OPTIONS] IMAGE...
```

## Common options

- `-f`: Force removal.
- `--no-prune`: Do not delete untagged parent images.

## Common examples

```bash
docker rmi myapp:old
docker rmi nginx:latest
```

## More options

This page covers selected high-frequency, practical options only. For the complete option list and details, see the [official Docker CLI documentation](https://docs.docker.com/reference/cli/docker/rmi/).
