+++
summary = "Resolve revision expressions and repository paths."
+++
---

## Purpose

Use this in scripts to get the repository root, current commit ID, or current branch name.

## Basic syntax

```bash
git rev-parse <expression>
```

## Common options

- `--show-toplevel`: Print the repository root.
- `--short HEAD`: Print the abbreviated current commit ID.
- `--abbrev-ref HEAD`: Print the current branch name.

## Common examples

```bash
git rev-parse --show-toplevel
git rev-parse --short HEAD
git rev-parse --abbrev-ref HEAD
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-rev-parse).
