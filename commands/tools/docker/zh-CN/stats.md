+++
summary = "实时查看容器资源使用情况。"
+++
---

## 用途

Display a live stream of container resource usage statistics.

## 基本语法

```bash
docker stats [选项] [容器...]
```

## 常用参数

- `--no-stream`：只输出一次。
- `--all`：显示所有容器。
- `--no-trunc`：显示完整容器 ID。

## 常用示例

```bash
docker stats
docker stats --no-stream
docker stats web
```

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [Docker CLI 官方文档](https://docs.docker.com/reference/cli/docker/stats/)。
