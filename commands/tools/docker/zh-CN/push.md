+++
summary = "将本机镜像推送到镜像仓库。"
+++
---

## 用途

Upload an image to a registry.

## 基本语法

```bash
docker push [选项] 镜像[:标签]
```

## 常用参数

- `-a`：推送仓库中的所有标签。
- `-q`：减少进度输出。

## 常用示例

```bash
docker tag myapp:1.0 username/myapp:1.0
docker push username/myapp:1.0
```

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [Docker CLI 官方文档](https://docs.docker.com/reference/cli/docker/push/)。
