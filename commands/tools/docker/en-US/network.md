+++
summary = "管理 Docker 网络。"
+++
---

## Purpose

Manage Docker networks.

## Basic syntax

```bash
docker network COMMAND
```

## Common options

- `ls`: List networks.
- `inspect`: Display network details.
- `create`: Create a network.
- `connect`: Connect a container to a network.
- `disconnect`: Disconnect a container.
- `rm`: Remove networks.
- `prune`: Remove unused networks.

## Common examples

```bash
docker network ls
docker network create app-net
docker network connect app-net web
docker network inspect app-net
docker network rm app-net
```

## More options

This page covers selected high-frequency, practical options only. For the complete option list and details, see the [official Docker CLI documentation](https://docs.docker.com/reference/cli/docker/network/).
