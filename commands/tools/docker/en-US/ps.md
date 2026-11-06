+++
summary = "列出容器。"
+++
---

## Purpose

List containers.

## Basic syntax

```bash
docker ps [OPTIONS]
```

## Common options

- `-a`: Show all containers, including stopped ones.
- `-q`: Show container IDs only.
- `-s`: Display container sizes.
- `--filter condition`: Filter the list.
- `--format template`: Customize output.
- `-n count`: Show the most recently created containers.

## Common examples

```bash
docker ps
docker ps -a
docker ps -q
docker ps --filter status=exited
```

## More options

This page covers selected high-frequency, practical options only. For the complete option list and details, see the [official Docker CLI documentation](https://docs.docker.com/reference/cli/docker/ps/).
