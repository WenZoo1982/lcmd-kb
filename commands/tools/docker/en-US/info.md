+++
summary = "显示 Docker 系统信息。"
+++
---

## Purpose

Display system-wide information about the Docker installation and daemon.

## Basic syntax

```bash
docker info [OPTIONS]
```

## Common options

- `--format template`: Format the output.

## Common examples

```bash
docker info
docker info --format '{{.ServerVersion}}'
```

## More options

This page covers selected high-frequency, practical options only. For the complete option list and details, see the [official Docker CLI documentation](https://docs.docker.com/reference/cli/docker/info/).
