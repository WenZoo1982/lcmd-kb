+++
summary = "向运行中的容器发送信号，默认发送 SIGKILL。"
+++
---

## 用途

Send a signal to one or more running containers; the default is SIGKILL.

## 基本语法

```bash
docker kill [选项] 容器...
```

## 常用参数

- `-s 信号`：指定要发送的信号。

## 常用示例

```bash
docker kill web
docker kill -s SIGTERM web
```

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [Docker CLI 官方文档](https://docs.docker.com/reference/cli/docker/kill/)。
