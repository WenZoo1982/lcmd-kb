+++
summary = "Switch branches or restore files using the legacy command."
+++
---

## Purpose

This command remains useful for older tutorials and scripts. Prefer `git switch` for branches and `git restore` for files.

## Basic syntax

```bash
git checkout <branch>
git checkout -b <new-branch>
git checkout -- <file>
```

## Common options

- `-b`: Create and switch to a new branch.
- `-- <file>`: Replace a working-tree file with the index version; uncommitted changes may be lost.

## Common examples

```bash
git checkout main
git checkout -b feature/login
git checkout -- README.md
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-checkout).
