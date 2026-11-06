+++
summary = "启动已创建或已停止的容器。"
+++
---

## 用途

Start one or more stopped containers.

## 基本语法

```bash
docker start [选项] 容器...
```

## 常用参数

- `-a`：连接容器标准输出/错误输出。
- `-i`：连接标准输入。

## 常用示例

```bash
docker start web
docker start -ai ubuntu-test
```

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [Docker CLI 官方文档](https://docs.docker.com/reference/cli/docker/start/)。
