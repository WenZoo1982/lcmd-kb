+++
summary = "向容器发送停止信号并停止运行。"
+++
---

## 用途

Stop one or more running containers gracefully.

## 基本语法

```bash
docker stop [选项] 容器...
```

## 常用参数

- `-t 秒数`：等待停止的超时时间，之后发送 SIGKILL。

## 常用示例

```bash
docker stop web
docker stop -t 30 web
```

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [Docker CLI 官方文档](https://docs.docker.com/reference/cli/docker/stop/)。
