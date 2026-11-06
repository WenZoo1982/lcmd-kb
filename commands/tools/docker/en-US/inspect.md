+++
summary = "查看 Docker 对象的详细配置和状态。"
+++
---

## Purpose

Return detailed configuration and state for Docker objects.

## Basic syntax

```bash
docker inspect [OPTIONS] OBJECT...
```

## Common options

- `-f template`: Format or select fields using a Go template.
- `-s`: Include container size information.
- `--type type`: Restrict the object type.

## Common examples

```bash
docker inspect web
docker inspect -f '{{.State.Status}}' web
docker inspect --type image nginx
```

## More options

This page covers selected high-frequency, practical options only. For the complete option list and details, see the [official Docker CLI documentation](https://docs.docker.com/reference/cli/docker/inspect/).
