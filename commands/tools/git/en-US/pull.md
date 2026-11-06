+++
summary = "Fetch remote changes and integrate them into the current branch."
+++
---

## Purpose

Use this to synchronize your current branch with its upstream branch. It performs a fetch followed by a merge or rebase.

## Basic syntax

```bash
git pull
git pull <remote> <branch>
```

## Common options

- `--rebase`: Reapply local commits on top of the fetched branch.
- `--ff-only`: Integrate only when a fast-forward is possible.
- `--no-rebase`: Use merge-based integration.

## Common examples

```bash
git pull
git pull --ff-only origin main
git pull --rebase
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-pull).
