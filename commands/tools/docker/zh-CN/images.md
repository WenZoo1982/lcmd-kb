+++
summary = "列出本机镜像。"
+++
---

## 用途

List images stored locally.

## 基本语法

```bash
docker images [选项] [仓库[:标签]]
```

## 常用参数

- `-a`：显示所有镜像层相关镜像。
- `-q`：只显示镜像 ID。
- `--digests`：显示摘要。
- `--filter 条件`：筛选镜像。

## 常用示例

```bash
docker images
docker images nginx
docker images -q
```

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [Docker CLI 官方文档](https://docs.docker.com/reference/cli/docker/images/)。
