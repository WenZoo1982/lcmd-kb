+++
summary = "初始化和管理 Docker Swarm 集群。"
+++
---

## Purpose

Initialize and manage a Docker Swarm cluster.

## Basic syntax

```bash
docker swarm COMMAND
```

## Common options

- `init`: Initialize a Swarm.
- `join`: Join a Swarm.
- `join-token`: Display join tokens.
- `leave`: Leave the Swarm.
- `update`: Update Swarm settings.

## Common examples

```bash
docker swarm init
docker swarm join-token worker
docker swarm leave
```

## More options

This page covers selected high-frequency, practical options only. For the complete option list and details, see the [official Docker CLI documentation](https://docs.docker.com/reference/cli/docker/swarm/).
