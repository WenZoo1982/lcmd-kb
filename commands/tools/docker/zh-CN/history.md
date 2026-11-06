+++
summary = "查看镜像的构建历史层。"
+++
---

## 用途

Show the history of an image, including its build layers.

## 基本语法

```bash
docker history [选项] 镜像
```

## 常用参数

- `--no-trunc`：显示完整命令。
- `-H`：显示创建时间。
- `-q`：只显示层 ID。

## 常用示例

```bash
docker history nginx
docker history --no-trunc myapp:1.0
```

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [Docker CLI 官方文档](https://docs.docker.com/reference/cli/docker/history/)。
