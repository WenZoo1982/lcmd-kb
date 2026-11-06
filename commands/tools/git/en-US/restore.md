+++
summary = "Restore working-tree files or unstage changes."
+++
---

## Purpose

Use this to discard uncommitted file edits or move staged changes back to the working tree.

## Basic syntax

```bash
git restore <file>
git restore --staged <file>
```

## Common options

- `--staged`: Unstage changes without changing working-tree files.
- `--source=<revision>`: Restore from a specific revision.
- `--worktree`: Restore working-tree files.

## Common examples

```bash
git restore README.md
git restore --staged README.md
git restore --source=HEAD~1 README.md
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-restore).
