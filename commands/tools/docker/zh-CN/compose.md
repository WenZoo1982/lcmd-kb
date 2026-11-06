+++
summary = "使用 Compose 文件定义和运行多容器应用。"
+++
---

## 用途

Define and run multi-container applications using a Compose file.

## 基本语法

```bash
docker compose 子命令
```

## 常用参数

- `up`：创建并启动服务。
- `down`：停止并移除项目容器和网络。
- `ps`：列出项目容器。
- `logs`：查看服务日志。
- `exec`：在服务容器内执行命令。
- `build`：构建或重新构建服务镜像。
- `pull`：拉取服务镜像。
- `restart`：重启服务容器。
- `stop` / `start`：停止或启动服务。
- `config`：验证并显示合并后的配置。

## 常用示例

```bash
docker compose up -d
docker compose ps
docker compose logs -f
docker compose exec app sh
docker compose down
```

## 更多参数

本文仅收录高频、实用的常见参数。如需了解完整参数及详细说明，请查阅 [Docker CLI 官方文档](https://docs.docker.com/reference/cli/docker/compose/)。
