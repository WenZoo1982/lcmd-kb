+++
summary = "删除一个或多个容器。"
+++
---

## Purpose

Remove one or more containers.

## Basic syntax

```bash
docker rm [OPTIONS] CONTAINER...
```

## Common options

- `-f`: Force removal of a running container.
- `-v`: Remove anonymous volumes associated with the container.

## Common examples

```bash
docker rm old-web
docker rm -f test-web
docker rm -v old-web
```

## More options

This page covers selected high-frequency, practical options only. For the complete option list and details, see the [official Docker CLI documentation](https://docs.docker.com/reference/cli/docker/rm/).
