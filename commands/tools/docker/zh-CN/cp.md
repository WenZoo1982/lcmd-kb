+++
summary = "在容器与本机之间复制文件或目录。"
+++
---

## 用途

Copy files or directories between a container and the local filesystem.

## 基本语法

```bash
docker cp [选项] 源路径 目标路径
```

## 常用参数

- `-a`：尽量保留源文件 UID/GID。
- `-L`：跟随源路径中的符号链接。

## 常用示例

```bash
docker cp ./config.yml web:/app/config.yml
docker cp web:/var/log/app.log .
```

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [Docker CLI 官方文档](https://docs.docker.com/reference/cli/docker/cp/)。
