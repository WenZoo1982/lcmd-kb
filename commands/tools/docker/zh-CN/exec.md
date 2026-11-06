+++
summary = "在运行中的容器内执行命令。"
+++
---

## 用途

Run a command inside a running container.

## 基本语法

```bash
docker exec [选项] 容器 命令
```

## 常用参数

- `-i`：保持标准输入打开。
- `-t`：分配伪终端。
- `-d`：后台执行。
- `-u 用户`：指定执行用户。
- `-w 目录`：指定容器内工作目录。
- `-e 名称=值`：设置临时环境变量。

## 常用示例

```bash
docker exec -it web sh
docker exec web ls /app
docker exec -u root -it web bash
```

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [Docker CLI 官方文档](https://docs.docker.com/reference/cli/docker/exec/)。
