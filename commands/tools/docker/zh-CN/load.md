+++
summary = "从 tar 归档或标准输入加载镜像。"
+++
---

## 用途

Load images from a tar archive or standard input.

## 基本语法

```bash
docker load [选项]
```

## 常用参数

- `-i 文件`：从文件读取镜像归档。
- `-q`：减少输出。

## 常用示例

```bash
docker load -i images.tar
docker load < images.tar
```

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [Docker CLI 官方文档](https://docs.docker.com/reference/cli/docker/load/)。
