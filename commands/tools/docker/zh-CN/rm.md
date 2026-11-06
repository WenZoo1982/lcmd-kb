+++
summary = "删除一个或多个容器。"
+++
---

## 用途

Remove one or more containers.

## 基本语法

```bash
docker rm [选项] 容器...
```

## 常用参数

- `-f`：强制删除运行中的容器。
- `-v`：同时删除关联的匿名卷。

## 常用示例

```bash
docker rm old-web
docker rm -f test-web
docker rm -v old-web
```

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [Docker CLI 官方文档](https://docs.docker.com/reference/cli/docker/rm/)。
