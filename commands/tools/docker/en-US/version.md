+++
summary = "显示 Docker 客户端和服务端版本信息。"
+++
---

## Purpose

Show Docker client and server version information.

## Basic syntax

```bash
docker version [OPTIONS]
```

## Common options

- `--format template`: Customize the output.

## Common examples

```bash
docker version
docker version --format '{{.Server.Version}}'
```

## More options

This page covers selected high-frequency, practical options only. For the complete option list and details, see the [official Docker CLI documentation](https://docs.docker.com/reference/cli/docker/version/).
