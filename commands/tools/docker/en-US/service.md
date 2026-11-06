+++
summary = "管理 Docker Swarm 服务。"
+++
---

## Purpose

Manage services in a Docker Swarm.

## Basic syntax

```bash
docker service COMMAND
```

## Common options

- `ls`: List services.
- `create`: Create a service.
- `ps`: List service tasks.
- `logs`: Fetch service logs.
- `scale`: Change replica count.
- `update`: Update service configuration.
- `rm`: Remove a service.

## Common examples

```bash
docker service ls
docker service create --name web -p 8080:80 nginx
docker service scale web=3
docker service ps web
```

## More options

This page covers selected high-frequency, practical options only. For the complete option list and details, see the [official Docker CLI documentation](https://docs.docker.com/reference/cli/docker/service/).
