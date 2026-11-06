+++
summary = "管理 Docker Swarm 配置对象。"
+++
---

## 用途

Manage Docker Swarm configs.

## 基本语法

```bash
docker config 子命令
```

## 常用参数

- `create`：创建配置对象。
- `ls`：列出配置。
- `inspect`：查看配置元数据。
- `rm`：删除配置。

## 常用示例

```bash
docker config create app_config ./app.conf
docker config ls
```

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [Docker CLI 官方文档](https://docs.docker.com/reference/cli/docker/config/)。
