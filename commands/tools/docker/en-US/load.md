+++
summary = "从 tar 归档或标准输入加载镜像。"
+++
---

## Purpose

Load images from a tar archive or standard input.

## Basic syntax

```bash
docker load [OPTIONS]
```

## Common options

- `-i file`: Read the image archive from a file.
- `-q`: Suppress progress output.

## Common examples

```bash
docker load -i images.tar
docker load < images.tar
```

## More options

This page covers selected high-frequency, practical options only. For the complete option list and details, see the [official Docker CLI documentation](https://docs.docker.com/reference/cli/docker/load/).
