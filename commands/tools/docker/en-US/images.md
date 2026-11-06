+++
summary = "列出本机镜像。"
+++
---

## Purpose

List images stored locally.

## Basic syntax

```bash
docker images [OPTIONS] [REPOSITORY[:TAG]]
```

## Common options

- `-a`: Show all images, including intermediate images.
- `-q`: Show image IDs only.
- `--digests`: Show image digests.
- `--filter condition`: Filter images.

## Common examples

```bash
docker images
docker images nginx
docker images -q
```

## More options

This page covers selected high-frequency, practical options only. For the complete option list and details, see the [official Docker CLI documentation](https://docs.docker.com/reference/cli/docker/images/).
