+++
summary = "列出容器。"
+++
---

## 用途

List containers.

## 基本语法

```bash
docker ps [选项]
```

## 常用参数

- `-a`：显示所有容器，包括已停止的。
- `-q`：只显示容器 ID。
- `-s`：显示容器大小。
- `--filter 条件`：筛选容器。
- `--format 模板`：自定义输出格式。
- `-n 数量`：显示最近创建的指定数量容器。

## 常用示例

```bash
docker ps
docker ps -a
docker ps -q
docker ps --filter status=exited
```

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [Docker CLI 官方文档](https://docs.docker.com/reference/cli/docker/ps/)。
