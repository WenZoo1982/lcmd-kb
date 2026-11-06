+++
summary = "从 tar 归档创建镜像。"
+++
---

## Purpose

Create an image from a filesystem tarball.

## Basic syntax

```bash
docker import [OPTIONS] FILE|URL [REPOSITORY[:TAG]]
```

## Common options

- `-c instruction`: Apply a Dockerfile-style configuration instruction.
- `-m message`: Add a commit message.

## Common examples

```bash
docker import rootfs.tar myimage:latest
```

## More options

This page covers selected high-frequency, practical options only. For the complete option list and details, see the [official Docker CLI documentation](https://docs.docker.com/reference/cli/docker/import/).
