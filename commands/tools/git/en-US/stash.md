+++
summary = "Temporarily save uncommitted changes."
+++
---

## Purpose

Use this when you need to switch tasks or branches without making a commit yet.

## Basic syntax

```bash
git stash
git stash pop
```

## Common options

- `-u`: Include untracked files.
- `list`: List saved stashes.
- `pop`: Restore and remove the latest stash.
- `apply`: Restore a stash but keep it in the list.

## Common examples

```bash
git stash -u
git stash list
git stash pop
git stash apply stash@{0}
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-stash).
