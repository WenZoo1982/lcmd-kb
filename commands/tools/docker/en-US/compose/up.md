+++
summary = "Create or update project services from a Compose file and start them."
+++
---

## Purpose

Create or update services defined in the Compose configuration in the current directory, then start their containers.

## Basic syntax

~~~bash
docker compose up [OPTIONS]
~~~

## Common options

| Goal | Command | Description |
|---|---|---|
| Start services | docker compose up | Create and start the configured services |
| Start in the background | docker compose up -d | Run services in detached mode |
| Rebuild before starting | docker compose up --build | Build or rebuild images before starting services |

## Common examples

~~~bash
docker compose up -d
~~~

## Notes

The Docker Compose plugin must be available, and the current directory must contain a valid Compose configuration file.
