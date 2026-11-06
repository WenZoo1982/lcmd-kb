+++
summary = "管理 Docker 数据卷。"
+++
---

## 用途

Manage Docker volumes.

## 基本语法

```bash
docker volume 子命令
```

## 常用参数

- `ls`：列出数据卷。
- `create`：创建数据卷。
- `inspect`：查看数据卷详情。
- `rm`：删除数据卷。
- `prune`：清理未使用的数据卷。

## 常用示例

```bash
docker volume ls
docker volume create app-data
docker volume inspect app-data
docker volume rm app-data
docker volume prune
```

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [Docker CLI 官方文档](https://docs.docker.com/reference/cli/docker/volume/)。
