+++
summary = "View and manage remote repository URLs."
+++
---

## Purpose

Use this to see which remote repositories are configured or to add and update a remote.

## Basic syntax

```bash
git remote -v
git remote add <name> <url>
```

## Common options

- `-v`: Show remote URLs.
- `add`: Add a remote.
- `set-url`: Change a remote URL.
- `remove`: Remove a remote configuration.

## Common examples

```bash
git remote -v
git remote add origin https://github.com/user/project.git
git remote set-url origin <new-url>
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-remote).
