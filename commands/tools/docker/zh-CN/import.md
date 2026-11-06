+++
summary = "从 tar 归档创建镜像。"
+++
---

## 用途

Create an image from a filesystem tarball.

## 基本语法

```bash
docker import [选项] 文件或 URL [仓库[:标签]]
```

## 常用参数

- `-c 指令`：应用 Dockerfile 风格的配置指令。
- `-m 信息`：添加提交说明。

## 常用示例

```bash
docker import rootfs.tar myimage:latest
```

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [Docker CLI 官方文档](https://docs.docker.com/reference/cli/docker/import/)。
