+++
summary = "Move or rename a tracked file."
+++
---

## Purpose

Use this to move or rename a file while updating Git's index.

## Basic syntax

```bash
git mv <source> <destination>
```

## Common options

- `-f`: Allow the destination to be overwritten.
- `-k`: Skip files that would cause an error.

## Common examples

```bash
git mv old-name.txt docs/new-name.txt
git status
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-mv).
