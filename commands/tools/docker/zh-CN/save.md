+++
summary = "将一个或多个镜像保存为 tar 归档。"
+++
---

## 用途

Save one or more images to a tar archive.

## 基本语法

```bash
docker save [选项] 镜像...
```

## 常用参数

- `-o 文件`：指定输出归档文件。

## 常用示例

```bash
docker save -o images.tar nginx:latest myapp:1.0
docker save nginx:latest > nginx.tar
```

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [Docker CLI 官方文档](https://docs.docker.com/reference/cli/docker/save/)。
