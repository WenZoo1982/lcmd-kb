+++
summary = "Create multiple working directories for one repository."
+++
---

## Purpose

Use this to work on multiple branches at the same time without repeatedly switching the current directory.

## Basic syntax

```bash
git worktree add <directory> <branch>
git worktree list
```

## Common options

- `add -b`: Create a new branch and its working directory.
- `list`: List working trees.
- `remove`: Remove a working tree.
- `prune`: Clean up stale records.

## Common examples

```bash
git worktree add ../project-hotfix hotfix
git worktree list
git worktree remove ../project-hotfix
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-worktree).
