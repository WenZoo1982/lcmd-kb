+++
summary = "为镜像添加名称或标签。"
+++
---

## Purpose

Create a tag that refers to a source image.

## Basic syntax

```bash
docker tag SOURCE_IMAGE[:TAG] TARGET_IMAGE[:TAG]
```

## Common options

There are no frequently used options that need separate listing for this command.

## Common examples

```bash
docker tag myapp:latest username/myapp:1.0
```

## More options

This page covers selected high-frequency, practical options only. For the complete option list and details, see the [official Docker CLI documentation](https://docs.docker.com/reference/cli/docker/tag/).
