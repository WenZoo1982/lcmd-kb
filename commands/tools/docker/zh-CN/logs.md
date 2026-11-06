+++
summary = "查看容器输出日志。"
+++
---

## 用途

Fetch logs produced by a container.

## 基本语法

```bash
docker logs [选项] 容器
```

## 常用参数

- `-f`：持续跟踪日志。
- `--tail 行数`：只显示末尾指定行数。
- `--since 时间`：显示指定时间之后的日志。
- `--timestamps`：显示时间戳。
- `--until 时间`：显示指定时间之前的日志。

## 常用示例

```bash
docker logs web
docker logs -f --tail 100 web
docker logs --since 30m web
```

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [Docker CLI 官方文档](https://docs.docker.com/reference/cli/docker/logs/)。
