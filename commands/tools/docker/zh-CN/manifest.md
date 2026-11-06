+++
summary = "管理多平台镜像清单。"
+++
---

## 用途

Manage image manifests and multi-platform image lists.

## 基本语法

```bash
docker manifest 子命令
```

## 常用参数

- `inspect`：查看清单。
- `create`：创建清单列表。
- `annotate`：为清单条目添加平台信息。
- `push`：推送清单。
- `rm`：删除本地清单列表。

## 常用示例

```bash
docker manifest inspect nginx
docker manifest create myapp:multi myapp:amd64 myapp:arm64
```

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [Docker CLI 官方文档](https://docs.docker.com/reference/cli/docker/manifest/)。
