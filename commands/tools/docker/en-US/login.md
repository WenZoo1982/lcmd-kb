+++
summary = "登录镜像仓库。"
+++
---

## Purpose

Authenticate to a container registry.

## Basic syntax

```bash
docker login [OPTIONS] [SERVER]
```

## Common options

- `-u user`: Set the username.
- `--password-stdin`: Read the password from standard input to avoid exposing it in shell history.

## Common examples

```bash
docker login
docker login -u myuser registry.example.com
echo "$TOKEN" | docker login -u myuser --password-stdin
```

## More options

This page covers selected high-frequency, practical options only. For the complete option list and details, see the [official Docker CLI documentation](https://docs.docker.com/reference/cli/docker/login/).
