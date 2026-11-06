+++
summary = "管理 Docker Swarm secrets。"
+++
---

## Purpose

Manage secrets in a Docker Swarm.

## Basic syntax

```bash
docker secret COMMAND
```

## Common options

- `create`: Create a secret.
- `ls`: List secrets.
- `inspect`: Inspect metadata.
- `rm`: Remove a secret.

## Common examples

```bash
printf '%s' 'secret-value' | docker secret create db_password -
docker secret ls
```

## More options

This page covers selected high-frequency, practical options only. For the complete option list and details, see the [official Docker CLI documentation](https://docs.docker.com/reference/cli/docker/secret/).
