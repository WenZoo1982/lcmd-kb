+++
summary = "更新容器的资源限制或重启策略。"
+++
---

## 用途

Update resource limits and restart policies for existing containers.

## 基本语法

```bash
docker update [选项] 容器...
```

## 常用参数

- `--memory 大小`：调整内存限制。
- `--cpus 数量`：调整 CPU 核心配额。
- `--restart 策略`：修改重启策略。
- `--memory-swap 大小`：设置内存与交换空间总限制。

## 常用示例

```bash
docker update --memory 1g web
docker update --cpus 2 web
docker update --restart unless-stopped web
```

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [Docker CLI 官方文档](https://docs.docker.com/reference/cli/docker/update/)。
