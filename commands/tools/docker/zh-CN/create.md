+++
summary = "创建容器但不启动。"
+++
---

## 用途

Create a container without starting it.

## 基本语法

```bash
docker create [选项] 镜像 [命令]
```

## 常用参数

- `--name 名称`：指定容器名称。
- `-p 主机端口:容器端口`：发布端口。
- `-v 卷或路径:容器路径`：挂载数据。
- `-e 名称=值`：设置环境变量。

## 常用示例

```bash
docker create --name web -p 8080:80 nginx
docker start web
```

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [Docker CLI 官方文档](https://docs.docker.com/reference/cli/docker/create/)。
