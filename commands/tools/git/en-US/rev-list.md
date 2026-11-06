+++
summary = "List commits reachable from a revision or range."
+++
---

## Purpose

Use this to count commits or list commits in a branch range, including in scripts.

## Basic syntax

```bash
git rev-list <range>
```

## Common options

- `--count`: Print only the number of commits.
- `--all`: Include commits reachable from all refs.

## Common examples

```bash
git rev-list --count HEAD
git rev-list --oneline main..feature
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-rev-list).
