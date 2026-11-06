+++
summary = "查看容器文件系统相对镜像的改动。"
+++
---

## 用途

Inspect changes to a container's filesystem compared with its image.

## 基本语法

```bash
docker diff 容器
```

## 常用参数

- `A`：新增文件或目录。
- `C`：修改文件或目录。
- `D`：删除文件或目录。

## 常用示例

```bash
docker diff web
```

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [Docker CLI 官方文档](https://docs.docker.com/reference/cli/docker/diff/)。
