+++
summary = "在 Docker Hub 搜索镜像。"
+++
---

## 用途

Search Docker Hub for images.

## 基本语法

```bash
docker search [选项] 关键词
```

## 常用参数

- `--filter 条件`：筛选结果，如 stars。
- `--limit 数量`：限制结果数量。
- `--no-trunc`：显示完整描述。

## 常用示例

```bash
docker search nginx
docker search --filter stars=100 nginx
```

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [Docker CLI 官方文档](https://docs.docker.com/reference/cli/docker/search/)。
