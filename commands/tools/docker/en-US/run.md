+++
summary = "创建并启动新容器。"
+++
---

## Purpose

Create and start a container from an image.

## Basic syntax

```bash
docker run [OPTIONS] IMAGE [COMMAND]
```

## Common options

- `-d`: Run in the background.
- `-it`: Keep stdin open and allocate a terminal.
- `--name name`: Assign a container name.
- `-p host:container`: Publish a port.
- `-v source:target`: Mount a volume or path.
- `--rm`: Remove the container when it exits.
- `--restart policy`: Set a restart policy.
- `-e name=value`: Set an environment variable.
- `--network network`: Connect to a network.
- `--memory size`: Set a memory limit.

## Common examples

```bash
docker run -d --name web -p 8080:80 nginx
docker run --rm -it ubuntu bash
docker run -d --restart unless-stopped --name db -e POSTGRES_PASSWORD=change-me postgres
```

## More options

This page covers selected high-frequency, practical options only. For the complete option list and details, see the [official Docker CLI documentation](https://docs.docker.com/reference/cli/docker/run/).
