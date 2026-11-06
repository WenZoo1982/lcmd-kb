+++
summary = "查看和管理 Docker 系统级资源。"
+++
---

## 用途

Manage Docker-wide resources and inspect daemon-level information.

## 基本语法

```bash
docker system 子命令
```

## 常用参数

- `df`：查看磁盘占用。
- `info`：查看系统信息。
- `prune`：清理未使用资源。
- `events`：查看服务事件。

## 常用示例

```bash
docker system df
docker system df -v
docker system prune
docker system prune -a
```

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [Docker CLI 官方文档](https://docs.docker.com/reference/cli/docker/system/)。
