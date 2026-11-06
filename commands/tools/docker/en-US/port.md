+++
summary = "查看容器端口映射。"
+++
---

## Purpose

List port mappings or a specific mapping for a container.

## Basic syntax

```bash
docker port CONTAINER [PRIVATE_PORT[/PROTO]]
```

## Common options

There are no frequently used options that need separate listing for this command.

## Common examples

```bash
docker port web
docker port web 80/tcp
```

## More options

This page covers selected high-frequency, practical options only. For the complete option list and details, see the [official Docker CLI documentation](https://docs.docker.com/reference/cli/docker/port/).
