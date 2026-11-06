+++
summary = "查看镜像的构建历史层。"
+++
---

## Purpose

Show the history of an image, including its build layers.

## Basic syntax

```bash
docker history [OPTIONS] IMAGE
```

## Common options

- `--no-trunc`: Show complete commands.
- `-H`: Show creation timestamps.
- `-q`: Show layer IDs only.

## Common examples

```bash
docker history nginx
docker history --no-trunc myapp:1.0
```

## More options

This page covers selected high-frequency, practical options only. For the complete option list and details, see the [official Docker CLI documentation](https://docs.docker.com/reference/cli/docker/history/).
