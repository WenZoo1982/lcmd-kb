+++
summary = "List files recorded in Git's index."
+++
---

## Purpose

Use this to see which files Git tracks or inspect the index.

## Basic syntax

```bash
git ls-files
```

## Common options

- `-m`: Show modified tracked files.
- `-o`: Show untracked files.
- `-s`: Include index details.

## Common examples

```bash
git ls-files
git ls-files -o --exclude-standard
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-ls-files).
