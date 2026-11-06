+++
summary = "管理容器检查点（实验性或平台相关功能）。"
+++
---

## 用途

Manage container checkpoints; availability depends on the Docker build and runtime configuration.

## 基本语法

```bash
docker checkpoint 子命令
```

## 常用参数

- `ls`：列出容器检查点。
- `create`：创建检查点。
- `rm`：删除检查点。

## 常用示例

```bash
docker checkpoint ls web
```

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [Docker CLI 官方文档](https://docs.docker.com/reference/cli/docker/checkpoint/)。
