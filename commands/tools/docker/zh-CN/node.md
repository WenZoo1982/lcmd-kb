+++
summary = "管理 Docker Swarm 节点。"
+++
---

## 用途

Manage nodes in a Docker Swarm.

## 基本语法

```bash
docker node 子命令
```

## 常用参数

- `ls`：列出节点。
- `inspect`：查看节点详情。
- `promote` / `demote`：提升或降级节点角色。
- `update`：更新节点配置。
- `rm`：移除节点。
- `ps`：查看节点任务。

## 常用示例

```bash
docker node ls
docker node inspect self
docker node ps self
```

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [Docker CLI 官方文档](https://docs.docker.com/reference/cli/docker/node/)。
