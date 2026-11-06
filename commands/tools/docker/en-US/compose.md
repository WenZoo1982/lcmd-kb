+++
summary = "使用 Compose 文件定义和运行多容器应用。"
+++
---

## Purpose

Define and run multi-container applications using a Compose file.

## Basic syntax

```bash
docker compose COMMAND
```

## Common options

- `up`: Create and start services.
- `down`: Stop and remove project containers and networks.
- `ps`: List project containers.
- `logs`: View service logs.
- `exec`: Run a command in a service container.
- `build`: Build or rebuild service images.
- `pull`: Pull service images.
- `restart`: Restart service containers.
- `stop` / `start`: Stop or start services.
- `config`: Validate and render the merged configuration.

## Common examples

```bash
docker compose up -d
docker compose ps
docker compose logs -f
docker compose exec app sh
docker compose down
```

## More options

This page covers selected high-frequency, practical options only. For the complete option list and details, see the [official Docker CLI documentation](https://docs.docker.com/reference/cli/docker/compose/).
