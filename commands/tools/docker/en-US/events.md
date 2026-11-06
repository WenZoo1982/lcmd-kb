+++
summary = "实时查看 Docker 服务事件。"
+++
---

## Purpose

Get real-time events from the Docker daemon.

## Basic syntax

```bash
docker events [OPTIONS]
```

## Common options

- `--since time`: Show events since a timestamp.
- `--until time`: Stop at a timestamp.
- `--filter condition`: Filter events.

## Common examples

```bash
docker events
docker events --since 1h
docker events --filter 'type=container'
```

## More options

This page covers selected high-frequency, practical options only. For the complete option list and details, see the [official Docker CLI documentation](https://docs.docker.com/reference/cli/docker/events/).
