+++
summary = "根据 Compose 配置创建并启动项目中的服务，支持后台运行。"
+++
---

## 用途

根据当前目录中的 Compose 配置文件创建或更新服务，并启动容器。

## 基本语法

```bash
docker compose up [选项]
```

## 常用参数

| 想要做什么 | 命令 | 说明 |
|---|---|---|
| 启动服务 | `docker compose up` | 创建并启动配置中的服务 |
| 后台启动 | `docker compose up -d` | 在后台运行服务 |
| 重新构建后启动 | `docker compose up --build` | 启动前构建或重新构建镜像 |

## 常用示例

```bash
docker compose up -d
```

## 必要注意事项

该命令要求 Docker Compose 插件可用，并且当前目录存在有效的 Compose 配置文件。
