+++
summary = "显示 Docker 系统信息。"
+++
---

## 用途

Display system-wide information about the Docker installation and daemon.

## 基本语法

```bash
docker info [选项]
```

## 常用参数

- `--format 模板`：按指定模板输出信息。

## 常用示例

```bash
docker info
docker info --format '{{.ServerVersion}}'
```

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [Docker CLI 官方文档](https://docs.docker.com/reference/cli/docker/info/)。
