+++
summary = "查看容器端口映射。"
+++
---

## 用途

List port mappings or a specific mapping for a container.

## 基本语法

```bash
docker port 容器 [私有端口[/协议]]
```

## 常用参数

此命令没有需要单独列出的高频参数。

## 常用示例

```bash
docker port web
docker port web 80/tcp
```

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [Docker CLI 官方文档](https://docs.docker.com/reference/cli/docker/port/)。
