+++
summary = "Remove files from Git tracking."
+++
---

## Purpose

Use this to delete a tracked file, or stop tracking a file while keeping the local copy.

## Basic syntax

```bash
git rm <file>
git rm --cached <file>
```

## Common options

- `--cached`: Remove from the index but keep the local file.
- `-r`: Remove a directory recursively.
- `-f`: Force removal of a file with local changes.

## Common examples

```bash
git rm old.txt
git rm --cached config.local
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-rm).
