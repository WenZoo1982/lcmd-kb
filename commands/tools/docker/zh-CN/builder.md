+++
summary = "管理镜像构建器。"
+++
---

## 用途

Manage BuildKit builders used by Docker builds.

## 基本语法

```bash
docker builder 命令
```

## 常用参数

- `docker builder ls`：列出构建缓存/构建器相关信息（具体子命令以版本为准）。
- `docker builder prune`：清理构建缓存。

## 常用示例

```bash
docker builder prune
docker builder prune -a
```

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [Docker CLI 官方文档](https://docs.docker.com/reference/cli/docker/builder/)。
