+++
summary = "管理镜像构建器。"
+++
---

## Purpose

Manage BuildKit builders used by Docker builds.

## Basic syntax

```bash
docker builder COMMAND
```

## Common options

- `docker builder prune`: Remove build cache.

## Common examples

```bash
docker builder prune
docker builder prune -a
```

## More options

This page covers selected high-frequency, practical options only. For the complete option list and details, see the [official Docker CLI documentation](https://docs.docker.com/reference/cli/docker/builder/).
