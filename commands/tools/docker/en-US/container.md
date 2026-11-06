+++
summary = "管理 Docker 容器。"
+++
---

## Purpose

Manage Docker containers.

## Basic syntax

```bash
docker container COMMAND
```

## Common options

- `ls`: List containers.
- `run`: Create and start a container.
- `exec`: Run a command in a running container.
- `logs`: Fetch container logs.
- `inspect`: Inspect a container.
- `start`, `stop`, `restart`: Control container state.
- `rm`: Remove containers.
- `prune`: Remove stopped containers.

## Common examples

```bash
docker container ls -a
docker container exec -it web sh
docker container logs -f web
docker container prune
```

## More options

This page covers selected high-frequency, practical options only. For the complete option list and details, see the [official Docker CLI documentation](https://docs.docker.com/reference/cli/docker/container/).
