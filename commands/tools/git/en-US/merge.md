+++
summary = "Merge another branch into the current branch."
+++
---

## Purpose

Use this to integrate a completed feature branch into a target branch.

## Basic syntax

```bash
git merge <branch>
```

## Common options

- `--no-ff`: Create a merge commit even when a fast-forward is possible.
- `--abort`: Stop a merge that is in progress.
- `--continue`: Continue after resolving conflicts.

## Common examples

```bash
git switch main
git merge feature/login
git merge --abort
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-merge).
