+++
summary = "Save staged changes as a new commit."
+++
---

## Purpose

Create a version record after reviewing and staging a set of changes.

## Basic syntax

```bash
git commit -m "commit message"
```

## Common options

- `-m`: Set the commit message inline.
- `-a`: Automatically stage modifications and deletions of tracked files; it does not include new files.
- `--amend`: Replace the latest commit; this can rewrite history.

## Common examples

```bash
git commit -m "Fix login issue"
git commit -am "Update configuration"
git commit --amend
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-commit).
