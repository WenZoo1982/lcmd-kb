+++
summary = "管理 Docker CLI 连接的 Docker daemon 上下文。"
+++
---

## 用途

Manage contexts that determine which Docker daemon the CLI connects to.

## 基本语法

```bash
docker context 子命令
```

## 常用参数

- `ls`：列出上下文。
- `show`：显示当前上下文。
- `use 名称`：切换上下文。
- `inspect`：查看上下文详情。
- `create`：创建上下文。
- `rm`：删除上下文。

## 常用示例

```bash
docker context ls
docker context show
docker context use default
docker context inspect default
```

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [Docker CLI 官方文档](https://docs.docker.com/reference/cli/docker/context/)。
