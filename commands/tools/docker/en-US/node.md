+++
summary = "管理 Docker Swarm 节点。"
+++
---

## Purpose

Manage nodes in a Docker Swarm.

## Basic syntax

```bash
docker node COMMAND
```

## Common options

- `ls`: List nodes.
- `inspect`: Inspect a node.
- `promote` / `demote`: Change node role.
- `update`: Update node settings.
- `rm`: Remove a node.
- `ps`: List tasks on a node.

## Common examples

```bash
docker node ls
docker node inspect self
docker node ps self
```

## More options

This page covers selected high-frequency, practical options only. For the complete option list and details, see the [official Docker CLI documentation](https://docs.docker.com/reference/cli/docker/node/).
