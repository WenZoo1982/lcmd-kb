+++
summary = "显示 Docker 客户端和服务端版本信息。"
+++
---

## 用途

Show Docker client and server version information.

## 基本语法

```bash
docker version [选项]
```

## 常用参数

- `--format 模板`：自定义输出格式。

## 常用示例

```bash
docker version
docker version --format '{{.Server.Version}}'
```

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [Docker CLI 官方文档](https://docs.docker.com/reference/cli/docker/version/)。
