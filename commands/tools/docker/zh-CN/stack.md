+++
summary = "部署和管理 Docker Swarm 应用栈。"
+++
---

## 用途

Deploy and manage a stack of services in Docker Swarm.

## 基本语法

```bash
docker stack 子命令
```

## 常用参数

- `deploy`：根据 Compose 格式文件部署栈。
- `ls`：列出栈。
- `services`：列出栈中的服务。
- `ps`：列出栈任务。
- `rm`：移除栈。

## 常用示例

```bash
docker stack deploy -c compose.yml mystack
docker stack services mystack
docker stack rm mystack
```

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [Docker CLI 官方文档](https://docs.docker.com/reference/cli/docker/stack/)。
