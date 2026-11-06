+++
summary = "将容器文件系统导出为 tar 归档。"
+++
---

## Purpose

Export a container filesystem as a tar archive.

## Basic syntax

```bash
docker export [OPTIONS] CONTAINER
```

## Common options

- `-o file`: Write the archive to a file.

## Common examples

```bash
docker export web -o web-rootfs.tar
```

## More options

This page covers selected high-frequency, practical options only. For the complete option list and details, see the [official Docker CLI documentation](https://docs.docker.com/reference/cli/docker/export/).
