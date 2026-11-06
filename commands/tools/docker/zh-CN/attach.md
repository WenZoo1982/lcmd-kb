+++
summary = "连接到正在运行的容器标准输入/输出。"
+++
---

## 用途

Attach your terminal to a running container's standard input, output, and error streams.

## 基本语法

```bash
docker attach [选项] 容器
```

## 常用参数

- `--no-stdin`：不连接标准输入。
- `--sig-proxy=false`：不将收到的信号转发给容器。

## 常用示例

```bash
docker attach web
```

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [Docker CLI 官方文档](https://docs.docker.com/reference/cli/docker/attach/)。
