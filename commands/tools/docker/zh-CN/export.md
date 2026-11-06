+++
summary = "将容器文件系统导出为 tar 归档。"
+++
---

## 用途

Export a container filesystem as a tar archive.

## 基本语法

```bash
docker export [选项] 容器
```

## 常用参数

- `-o 文件`：将归档写入文件。

## 常用示例

```bash
docker export web -o web-rootfs.tar
```

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [Docker CLI 官方文档](https://docs.docker.com/reference/cli/docker/export/)。
