+++
summary = "在运行中的容器内执行命令。"
+++
---

## Purpose

Run a command inside a running container.

## Basic syntax

```bash
docker exec [OPTIONS] CONTAINER COMMAND
```

## Common options

- `-i`: Keep standard input open.
- `-t`: Allocate a pseudo-TTY.
- `-d`: Run in the background.
- `-u user`: Set the execution user.
- `-w dir`: Set the working directory.
- `-e name=value`: Set an environment variable.

## Common examples

```bash
docker exec -it web sh
docker exec web ls /app
docker exec -u root -it web bash
```

## More options

This page covers selected high-frequency, practical options only. For the complete option list and details, see the [official Docker CLI documentation](https://docs.docker.com/reference/cli/docker/exec/).
