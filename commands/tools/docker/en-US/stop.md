+++
summary = "向容器发送停止信号并停止运行。"
+++
---

## Purpose

Stop one or more running containers gracefully.

## Basic syntax

```bash
docker stop [OPTIONS] CONTAINER...
```

## Common options

- `-t seconds`: Wait this long before sending SIGKILL.

## Common examples

```bash
docker stop web
docker stop -t 30 web
```

## More options

This page covers selected high-frequency, practical options only. For the complete option list and details, see the [official Docker CLI documentation](https://docs.docker.com/reference/cli/docker/stop/).
