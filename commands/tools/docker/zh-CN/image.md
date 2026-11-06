+++
summary = "管理 Docker 镜像。"
+++
---

## 用途

Manage Docker images.

## 基本语法

```bash
docker image 子命令
```

## 常用参数

- `ls`：列出镜像。
- `pull`：拉取镜像。
- `push`：推送镜像。
- `rm`：删除镜像。
- `inspect`：查看镜像详情。
- `prune`：清理未使用镜像。
- `tag`：为镜像添加标签。
- `save` / `load`：导出或导入镜像归档。

## 常用示例

```bash
docker image ls
docker image pull nginx
docker image inspect nginx
docker image prune
docker image rm nginx
```

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [Docker CLI 官方文档](https://docs.docker.com/reference/cli/docker/image/)。
