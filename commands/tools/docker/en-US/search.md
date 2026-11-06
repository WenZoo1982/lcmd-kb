+++
summary = "在 Docker Hub 搜索镜像。"
+++
---

## Purpose

Search Docker Hub for images.

## Basic syntax

```bash
docker search [OPTIONS] TERM
```

## Common options

- `--filter condition`: Filter results, for example by stars.
- `--limit count`: Limit the number of results.
- `--no-trunc`: Show full descriptions.

## Common examples

```bash
docker search nginx
docker search --filter stars=100 nginx
```

## More options

This page covers selected high-frequency, practical options only. For the complete option list and details, see the [official Docker CLI documentation](https://docs.docker.com/reference/cli/docker/search/).
