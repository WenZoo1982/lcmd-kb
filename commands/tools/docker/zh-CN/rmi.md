+++
summary = "删除一个或多个本机镜像。"
+++
---

## 用途

Remove one or more local images.

## 基本语法

```bash
docker rmi [选项] 镜像...
```

## 常用参数

- `-f`：强制删除镜像。
- `-no-prune`：不删除未标记的父镜像。

## 常用示例

```bash
docker rmi myapp:old
docker rmi nginx:latest
```

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [Docker CLI 官方文档](https://docs.docker.com/reference/cli/docker/rmi/)。
