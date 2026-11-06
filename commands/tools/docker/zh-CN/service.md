+++
summary = "管理 Docker Swarm 服务。"
+++
---

## 用途

Manage services in a Docker Swarm.

## 基本语法

```bash
docker service 子命令
```

## 常用参数

- `ls`：列出服务。
- `create`：创建服务。
- `ps`：查看服务任务。
- `logs`：查看服务日志。
- `scale`：调整副本数量。
- `update`：更新服务配置。
- `rm`：删除服务。

## 常用示例

```bash
docker service ls
docker service create --name web -p 8080:80 nginx
docker service scale web=3
docker service ps web
```

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [Docker CLI 官方文档](https://docs.docker.com/reference/cli/docker/service/)。
