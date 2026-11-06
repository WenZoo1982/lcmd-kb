+++
summary = "启动已创建或已停止的容器。"
+++
---

## Purpose

Start one or more stopped containers.

## Basic syntax

```bash
docker start [OPTIONS] CONTAINER...
```

## Common options

- `-a`: Attach to standard output and error.
- `-i`: Attach to standard input.

## Common examples

```bash
docker start web
docker start -ai ubuntu-test
```

## More options

This page covers selected high-frequency, practical options only. For the complete option list and details, see the [official Docker CLI documentation](https://docs.docker.com/reference/cli/docker/start/).
