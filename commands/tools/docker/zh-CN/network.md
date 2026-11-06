+++
summary = "管理 Docker 网络。"
+++
---

## 用途

Manage Docker networks.

## 基本语法

```bash
docker network 子命令
```

## 常用参数

- `ls`：列出网络。
- `inspect`：查看网络详情。
- `create`：创建网络。
- `connect`：将容器连接到网络。
- `disconnect`：断开容器网络连接。
- `rm`：删除网络。
- `prune`：清理未使用网络。

## 常用示例

```bash
docker network ls
docker network create app-net
docker network connect app-net web
docker network inspect app-net
docker network rm app-net
```

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [Docker CLI 官方文档](https://docs.docker.com/reference/cli/docker/network/)。
