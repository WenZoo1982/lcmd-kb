+++
summary = "Quick reference for practical Docker CLI commands covering containers, images, networking, volumes, Compose, and Swarm."
+++
---

# Docker command quick reference

This section covers Docker CLI commands with practical value for everyday container work, image management, persistent storage, networking, builds, Compose, and Swarm.

## Container operations
- `run`, `create`, `start`, `stop`, `restart`, `pause`, `unpause`, `kill`, `wait`
- `ps`, `exec`, `attach`, `logs`, `top`, `stats`, `inspect`, `diff`, `port`, `cp`, `rename`, `rm`

## Images and builds
- `build`, `builder`, `images`, `image`, `pull`, `push`, `tag`, `rmi`, `history`, `commit`, `save`, `load`, `import`, `export`, `search`, `manifest`

## Networking, storage, and system
- `network`, `volume`, `system`, `info`, `events`, `context`, `version`

## Multi-container applications and clusters
- `compose` — Compose applications
- `swarm`, `node`, `service`, `stack`, `secret`, `config` — Swarm administration

## Other management commands
- `login`, `logout`, `plugin`, `update`, `checkpoint`

## Scope

This set includes Docker CLI commands useful for development, operations, image publishing, networking, storage, and cluster management. Some features (including Swarm, checkpoints, and plugins) depend on the Docker version, operating mode, or platform and may not be available everywhere. Docker Compose V2 is presented as the `docker compose` plugin; the legacy standalone `docker-compose` command is not the primary format here.

## More information

These pages are quick references, not complete manuals. Check command availability against your installed Docker Engine, CLI, and Compose versions.
