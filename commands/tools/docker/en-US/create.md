+++
summary = "创建容器但不启动。"
+++
---

## Purpose

Create a container without starting it.

## Basic syntax

```bash
docker create [OPTIONS] IMAGE [COMMAND]
```

## Common options

- `--name name`: Assign a container name.
- `-p host:container`: Publish a port.
- `-v source:target`: Mount a volume or path.
- `-e name=value`: Set an environment variable.

## Common examples

```bash
docker create --name web -p 8080:80 nginx
docker start web
```

## More options

This page covers selected high-frequency, practical options only. For the complete option list and details, see the [official Docker CLI documentation](https://docs.docker.com/reference/cli/docker/create/).
