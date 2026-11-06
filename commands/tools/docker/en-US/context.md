+++
summary = "管理 Docker CLI 连接的 Docker daemon 上下文。"
+++
---

## Purpose

Manage contexts that determine which Docker daemon the CLI connects to.

## Basic syntax

```bash
docker context COMMAND
```

## Common options

- `ls`: List contexts.
- `show`: Display the current context.
- `use name`: Switch contexts.
- `inspect`: Inspect a context.
- `create`: Create a context.
- `rm`: Remove a context.

## Common examples

```bash
docker context ls
docker context show
docker context use default
docker context inspect default
```

## More options

This page covers selected high-frequency, practical options only. For the complete option list and details, see the [official Docker CLI documentation](https://docs.docker.com/reference/cli/docker/context/).
