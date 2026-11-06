+++
summary = "管理容器检查点（实验性或平台相关功能）。"
+++
---

## Purpose

Manage container checkpoints; availability depends on the Docker build and runtime configuration.

## Basic syntax

```bash
docker checkpoint COMMAND
```

## Common options

- `ls`: List container checkpoints.
- `create`: Create a checkpoint.
- `rm`: Remove a checkpoint.

## Common examples

```bash
docker checkpoint ls web
```

## More options

This page covers selected high-frequency, practical options only. For the complete option list and details, see the [official Docker CLI documentation](https://docs.docker.com/reference/cli/docker/checkpoint/).
