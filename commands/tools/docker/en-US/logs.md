+++
summary = "查看容器输出日志。"
+++
---

## Purpose

Fetch logs produced by a container.

## Basic syntax

```bash
docker logs [OPTIONS] CONTAINER
```

## Common options

- `-f`: Follow log output.
- `--tail number`: Show only the specified number of recent lines.
- `--since time`: Show logs since a timestamp or duration.
- `--timestamps`: Show timestamps.
- `--until time`: Show logs up to a timestamp.

## Common examples

```bash
docker logs web
docker logs -f --tail 100 web
docker logs --since 30m web
```

## More options

This page covers selected high-frequency, practical options only. For the complete option list and details, see the [official Docker CLI documentation](https://docs.docker.com/reference/cli/docker/logs/).
