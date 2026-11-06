+++
summary = "重启一个或多个容器。"
+++
---

## 用途

Restart one or more containers.

## 基本语法

```bash
docker restart [选项] 容器...
```

## 常用参数

- `-t 秒数`：等待容器停止的超时时间。

## 常用示例

```bash
docker restart web
docker restart -t 30 web
```

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [Docker CLI 官方文档](https://docs.docker.com/reference/cli/docker/restart/)。
