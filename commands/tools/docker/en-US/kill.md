+++
summary = "向运行中的容器发送信号，默认发送 SIGKILL。"
+++
---

## Purpose

Send a signal to one or more running containers; the default is SIGKILL.

## Basic syntax

```bash
docker kill [OPTIONS] CONTAINER...
```

## Common options

- `-s SIGNAL`: Specify the signal to send.

## Common examples

```bash
docker kill web
docker kill -s SIGTERM web
```

## More options

This page covers selected high-frequency, practical options only. For the complete option list and details, see the [official Docker CLI documentation](https://docs.docker.com/reference/cli/docker/kill/).
