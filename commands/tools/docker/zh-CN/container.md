+++
summary = "管理 Docker 容器。"
+++
---

## 用途

Manage Docker containers.

## 基本语法

```bash
docker container 子命令
```

## 常用参数

- `ls`：列出容器。
- `run`：创建并启动容器。
- `exec`：在运行中容器内执行命令。
- `logs`：查看日志。
- `inspect`：查看详情。
- `start`、`stop`、`restart`：控制容器运行状态。
- `rm`：删除容器。
- `prune`：清理已停止容器。

## 常用示例

```bash
docker container ls -a
docker container exec -it web sh
docker container logs -f web
docker container prune
```

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [Docker CLI 官方文档](https://docs.docker.com/reference/cli/docker/container/)。
