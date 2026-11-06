+++
summary = "根据 Dockerfile 构建镜像。"
+++
---

## 用途

Build an image from a Dockerfile and build context.

## 基本语法

```bash
docker build [选项] 路径
```

## 常用参数

- `-t 名称:标签`：指定镜像名称和标签。
- `-f 文件`：指定 Dockerfile。
- `--no-cache`：不使用构建缓存。
- `--pull`：尝试拉取更新的基础镜像。
- `--build-arg 名称=值`：传入构建参数。
- `--platform 平台`：指定目标平台。

## 常用示例

```bash
docker build -t myapp:1.0 .
docker build -f docker/Dockerfile -t myapp .
docker build --no-cache -t myapp:debug .
```

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [Docker CLI 官方文档](https://docs.docker.com/reference/cli/docker/build/)。
