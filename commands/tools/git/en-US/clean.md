+++
summary = "Remove untracked files from the working tree."
+++
---

## Purpose

Use this to remove generated files and temporary files that Git does not track. Preview first: deleted files are not normally recoverable through Git.

## Basic syntax

```bash
git clean -n
git clean -f
```

## Common options

- `-n`: Preview what would be removed.
- `-f`: Actually remove untracked files.
- `-d`: Also remove untracked directories.
- `-x`: Also remove ignored files; use with care.

## Common examples

```bash
git clean -n
git clean -fd
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-clean).
