+++
summary = "管理 Docker Swarm secrets。"
+++
---

## 用途

Manage secrets in a Docker Swarm.

## 基本语法

```bash
docker secret 子命令
```

## 常用参数

- `create`：创建 secret。
- `ls`：列出 secret。
- `inspect`：查看元数据。
- `rm`：删除 secret。

## 常用示例

```bash
printf '%s' 'secret-value' | docker secret create db_password -
docker secret ls
```

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [Docker CLI 官方文档](https://docs.docker.com/reference/cli/docker/secret/)。
