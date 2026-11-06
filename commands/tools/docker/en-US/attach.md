+++
summary = "连接到正在运行的容器标准输入/输出。"
+++
---

## Purpose

Attach your terminal to a running container's standard input, output, and error streams.

## Basic syntax

```bash
docker attach [OPTIONS] CONTAINER
```

## Common options

- `--no-stdin`: Do not attach standard input.
- `--sig-proxy=false`: Do not proxy received signals to the container.

## Common examples

```bash
docker attach web
```

## More options

This page covers selected high-frequency, practical options only. For the complete option list and details, see the [official Docker CLI documentation](https://docs.docker.com/reference/cli/docker/attach/).
