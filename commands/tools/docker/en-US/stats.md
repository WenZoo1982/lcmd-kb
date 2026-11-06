+++
summary = "实时查看容器资源使用情况。"
+++
---

## Purpose

Display a live stream of container resource usage statistics.

## Basic syntax

```bash
docker stats [OPTIONS] [CONTAINER...]
```

## Common options

- `--no-stream`: Print a single snapshot.
- `--all`: Show all containers.
- `--no-trunc`: Show full container IDs.

## Common examples

```bash
docker stats
docker stats --no-stream
docker stats web
```

## More options

This page covers selected high-frequency, practical options only. For the complete option list and details, see the [official Docker CLI documentation](https://docs.docker.com/reference/cli/docker/stats/).
