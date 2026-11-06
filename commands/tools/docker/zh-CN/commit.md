+++
summary = "将容器当前文件系统状态保存为新镜像。"
+++
---

## 用途

Create a new image from a container's current filesystem changes.

## 基本语法

```bash
docker commit [选项] 容器 [镜像[:标签]]
```

## 常用参数

- `-a 作者`：设置作者信息。
- `-m 信息`：添加提交说明。
- `-p`：提交时暂停容器。

## 常用示例

```bash
docker commit web myapp:snapshot
docker commit -m "before upgrade" web myapp:backup
```

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [Docker CLI 官方文档](https://docs.docker.com/reference/cli/docker/commit/)。
