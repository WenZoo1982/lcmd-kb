+++
summary = "管理多平台镜像清单。"
+++
---

## Purpose

Manage image manifests and multi-platform image lists.

## Basic syntax

```bash
docker manifest COMMAND
```

## Common options

- `inspect`: Inspect a manifest.
- `create`: Create a manifest list.
- `annotate`: Add platform metadata to an entry.
- `push`: Push a manifest list.
- `rm`: Delete a local manifest list.

## Common examples

```bash
docker manifest inspect nginx
docker manifest create myapp:multi myapp:amd64 myapp:arm64
```

## More options

This page covers selected high-frequency, practical options only. For the complete option list and details, see the [official Docker CLI documentation](https://docs.docker.com/reference/cli/docker/manifest/).
