+++
summary = "根据镜像创建并启动容器，设置端口、名称和后台运行方式。"
+++

## 用途

使用指定镜像创建并启动一个容器。

## 基本语法

```bash
docker run [选项] 镜像 [命令]
```

## 常用参数

| 想要做什么 | 命令 | 说明 |
|---|---|---|
| 后台运行 | `docker run -d nginx` | 在后台启动容器 |
| 设置容器名称 | `docker run --name web nginx` | 将容器命名为 web |
| 映射端口 | `docker run -p 8080:80 nginx` | 将主机 8080 映射到容器 80 |

## 常用示例

```bash
docker run -d --name web -p 8080:80 nginx
```

## 必要注意事项

运行容器前需要本地存在对应镜像，或允许 Docker 从镜像仓库拉取镜像。
