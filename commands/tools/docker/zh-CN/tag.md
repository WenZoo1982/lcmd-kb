+++
summary = "为镜像添加名称或标签。"
+++
---

## 用途

Create a tag that refers to a source image.

## 基本语法

```bash
docker tag 源镜像[:标签] 目标镜像[:标签]
```

## 常用参数

此命令没有需要单独列出的高频参数。

## 常用示例

```bash
docker tag myapp:latest username/myapp:1.0
```

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [Docker CLI 官方文档](https://docs.docker.com/reference/cli/docker/tag/)。
