+++
summary = "登录镜像仓库。"
+++
---

## 用途

Authenticate to a container registry.

## 基本语法

```bash
docker login [选项] [服务器]
```

## 常用参数

- `-u 用户`：指定用户名。
- `--password-stdin`：从标准输入读取密码，避免密码出现在命令历史中。

## 常用示例

```bash
docker login
docker login -u myuser registry.example.com
echo "$TOKEN" | docker login -u myuser --password-stdin
```

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [Docker CLI 官方文档](https://docs.docker.com/reference/cli/docker/login/)。
