+++
summary = "部署和管理 Docker Swarm 应用栈。"
+++
---

## Purpose

Deploy and manage a stack of services in Docker Swarm.

## Basic syntax

```bash
docker stack COMMAND
```

## Common options

- `deploy`: Deploy a stack from a Compose-format file.
- `ls`: List stacks.
- `services`: List services in a stack.
- `ps`: List stack tasks.
- `rm`: Remove a stack.

## Common examples

```bash
docker stack deploy -c compose.yml mystack
docker stack services mystack
docker stack rm mystack
```

## More options

This page covers selected high-frequency, practical options only. For the complete option list and details, see the [official Docker CLI documentation](https://docs.docker.com/reference/cli/docker/stack/).
