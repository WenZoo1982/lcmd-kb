+++
summary = "List, create, rename, or delete branches."
+++
---

## Purpose

Use this to manage branches. Prefer `git switch` when changing branches.

## Basic syntax

```bash
git branch
git branch <new-branch>
git branch -d <branch>
```

## Common options

- `-a`: List local and remote-tracking branches.
- `-r`: List remote-tracking branches only.
- `-d`: Delete a branch that has been merged.
- `-D`: Force-delete a branch.
- `-m`: Rename a branch.

## Common examples

```bash
git branch -a
git branch feature/login
git branch -d feature/login
git branch -m old-name new-name
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-branch).
