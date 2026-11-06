+++
summary = "Display details about a commit, tag, or Git object."
+++
---

## Purpose

Use this to inspect a commit's changes or read a file from a specific revision.

## Basic syntax

```bash
git show [commit-or-object]
```

## Common options

- `--stat`: Show a change summary.
- `--name-only`: Show changed file names only.
- `--format=oneline`: Use a compact commit summary.

## Common examples

```bash
git show
git show --stat HEAD
git show HEAD~1:README.md
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-show).
