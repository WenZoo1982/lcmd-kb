+++
summary = "查看 Docker 对象的详细配置和状态。"
+++
---

## 用途

Return detailed configuration and state for Docker objects.

## 基本语法

```bash
docker inspect [选项] 对象...
```

## 常用参数

- `-f 模板`：按 Go 模板筛选字段。
- `-s`：显示容器大小（适用于容器）。
- `--type 类型`：限定对象类型。

## 常用示例

```bash
docker inspect web
docker inspect -f '{{.State.Status}}' web
docker inspect --type image nginx
```

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [Docker CLI 官方文档](https://docs.docker.com/reference/cli/docker/inspect/)。
