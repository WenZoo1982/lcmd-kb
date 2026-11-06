+++
summary = "实时查看 Docker 服务事件。"
+++
---

## 用途

Get real-time events from the Docker daemon.

## 基本语法

```bash
docker events [选项]
```

## 常用参数

- `--since 时间`：从指定时间开始。
- `--until 时间`：读取到指定时间结束。
- `--filter 条件`：筛选事件。

## 常用示例

```bash
docker events
docker events --since 1h
docker events --filter 'type=container'
```

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [Docker CLI 官方文档](https://docs.docker.com/reference/cli/docker/events/)。
