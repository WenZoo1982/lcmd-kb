+++
summary = "从镜像仓库下载镜像。"
+++
---

## 用途

Download an image or repository from a registry.

## 基本语法

```bash
docker pull [选项] 镜像[:标签|@摘要]
```

## 常用参数

- `-a`：拉取仓库中的所有标签。
- `--platform 平台`：指定目标平台。
- `-q`：减少进度输出。

## 常用示例

```bash
docker pull nginx
docker pull nginx:alpine
docker pull --platform linux/arm64 nginx
```

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [Docker CLI 官方文档](https://docs.docker.com/reference/cli/docker/pull/)。
