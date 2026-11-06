+++
summary = "更新容器的资源限制或重启策略。"
+++
---

## Purpose

Update resource limits and restart policies for existing containers.

## Basic syntax

```bash
docker update [OPTIONS] CONTAINER...
```

## Common options

- `--memory size`: Update the memory limit.
- `--cpus number`: Set the CPU quota in cores.
- `--restart policy`: Change the restart policy.
- `--memory-swap size`: Set the memory-plus-swap limit.

## Common examples

```bash
docker update --memory 1g web
docker update --cpus 2 web
docker update --restart unless-stopped web
```

## More options

This page covers selected high-frequency, practical options only. For the complete option list and details, see the [official Docker CLI documentation](https://docs.docker.com/reference/cli/docker/update/).
