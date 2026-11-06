+++
summary = "创建并启动新容器。"
+++
---

## 用途

Create and start a container from an image.

## 基本语法

```bash
docker run [选项] 镜像 [命令]
```

## 常用参数

- `-d`：后台运行。
- `-it`：交互运行并分配终端。
- `--name 名称`：指定容器名称。
- `-p 主机端口:容器端口`：发布端口。
- `-v 卷或路径:容器路径`：挂载数据。
- `--rm`：容器退出后自动删除。
- `--restart 策略`：设置重启策略。
- `-e 名称=值`：设置环境变量。
- `--network 网络`：指定网络。
- `--memory 大小`：限制内存。

## 常用示例

```bash
docker run -d --name web -p 8080:80 nginx
docker run --rm -it ubuntu bash
docker run -d --restart unless-stopped --name db -e POSTGRES_PASSWORD=change-me postgres
```

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [Docker CLI 官方文档](https://docs.docker.com/reference/cli/docker/run/)。
