+++
summary = "重启一个或多个容器。"
+++
---

## Purpose

Restart one or more containers.

## Basic syntax

```bash
docker restart [OPTIONS] CONTAINER...
```

## Common options

- `-t seconds`: Set the shutdown timeout before sending SIGKILL.

## Common examples

```bash
docker restart web
docker restart -t 30 web
```

## More options

This page covers selected high-frequency, practical options only. For the complete option list and details, see the [official Docker CLI documentation](https://docs.docker.com/reference/cli/docker/restart/).
