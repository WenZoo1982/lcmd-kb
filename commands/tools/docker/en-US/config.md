+++
summary = "管理 Docker Swarm 配置对象。"
+++
---

## Purpose

Manage Docker Swarm configs.

## Basic syntax

```bash
docker config COMMAND
```

## Common options

- `create`: Create a config object.
- `ls`: List configs.
- `inspect`: Inspect config metadata.
- `rm`: Remove a config.

## Common examples

```bash
docker config create app_config ./app.conf
docker config ls
```

## More options

This page covers selected high-frequency, practical options only. For the complete option list and details, see the [official Docker CLI documentation](https://docs.docker.com/reference/cli/docker/config/).
