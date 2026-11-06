+++
summary = "管理 Docker 数据卷。"
+++
---

## Purpose

Manage Docker volumes.

## Basic syntax

```bash
docker volume COMMAND
```

## Common options

- `ls`: List volumes.
- `create`: Create a volume.
- `inspect`: Display volume details.
- `rm`: Remove volumes.
- `prune`: Remove unused volumes.

## Common examples

```bash
docker volume ls
docker volume create app-data
docker volume inspect app-data
docker volume rm app-data
docker volume prune
```

## More options

This page covers selected high-frequency, practical options only. For the complete option list and details, see the [official Docker CLI documentation](https://docs.docker.com/reference/cli/docker/volume/).
