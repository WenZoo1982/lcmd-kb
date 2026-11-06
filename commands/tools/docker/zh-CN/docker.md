+++
summary = "Docker CLI 常用命令速查，涵盖容器、镜像、网络、数据卷、Compose 与 Swarm。"
+++
---

# Docker 命令速查

本目录整理 Docker CLI 中具有实际使用价值的命令，重点覆盖日常容器操作、镜像管理、数据持久化、网络、构建、Compose 和 Swarm。

## 基础操作
- `run`、`create`、`start`、`stop`、`restart`、`pause`、`unpause`、`kill`、`wait`
- `ps`、`exec`、`attach`、`logs`、`top`、`stats`、`inspect`、`diff`、`port`、`cp`、`rename`、`rm`

## 镜像与构建
- `build`、`builder`、`images`、`image`、`pull`、`push`、`tag`、`rmi`、`history`、`commit`、`save`、`load`、`import`、`export`、`search`、`manifest`

## 网络、存储与系统
- `network`、`volume`、`system`、`info`、`events`、`context`、`version`

## 多容器与集群
- `compose` — Compose 多容器应用
- `swarm`、`node`、`service`、`stack`、`secret`、`config` — Swarm 集群管理

## 其他管理命令
- `login`、`logout`、`plugin`、`update`、`checkpoint`

## 范围说明

收录 Docker CLI 中日常运维、开发、镜像发布、网络存储及集群管理中有实际用途的命令。某些功能（例如 Swarm、checkpoint、插件管理）依赖 Docker 版本、运行模式或平台，不保证所有环境均可用。Docker Compose V2 以 `docker compose` 插件形式提供；旧版独立 `docker-compose` 不作为本目录的主命令格式。

## 更多信息

本文档用于快速查找，不替代官方手册。请结合当前 Docker Engine、CLI 和 Compose 版本确认命令是否可用。
