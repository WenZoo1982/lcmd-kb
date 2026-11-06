+++
summary = "初始化和管理 Docker Swarm 集群。"
+++
---

## 用途

Initialize and manage a Docker Swarm cluster.

## 基本语法

```bash
docker swarm 子命令
```

## 常用参数

- `init`：初始化 Swarm。
- `join`：加入集群。
- `join-token`：显示加入令牌。
- `leave`：离开集群。
- `update`：更新集群配置。

## 常用示例

```bash
docker swarm init
docker swarm join-token worker
docker swarm leave
```

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [Docker CLI 官方文档](https://docs.docker.com/reference/cli/docker/swarm/)。
