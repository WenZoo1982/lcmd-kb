+++
summary = "查看和管理 Docker 系统级资源。"
+++
---

## Purpose

Manage Docker-wide resources and inspect daemon-level information.

## Basic syntax

```bash
docker system COMMAND
```

## Common options

- `df`: Show Docker disk usage.
- `info`: Display system information.
- `prune`: Remove unused resources.
- `events`: Get daemon events.

## Common examples

```bash
docker system df
docker system df -v
docker system prune
docker system prune -a
```

## More options

This page covers selected high-frequency, practical options only. For the complete option list and details, see the [official Docker CLI documentation](https://docs.docker.com/reference/cli/docker/system/).
