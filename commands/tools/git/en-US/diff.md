+++
summary = "Show changes between files, the working tree, and commits."
+++
---

## Purpose

Use this to review exactly what changed before committing or when comparing revisions.

## Basic syntax

```bash
git diff
git diff --staged
git diff <revision-1> <revision-2>
```

## Common options

- Default: Compare the working tree with the index.
- `--staged`: Show changes staged for the next commit.
- `--stat`: Show a summary instead of the full patch.
- `-- <file>`: Limit the comparison to one file.

## Common examples

```bash
git diff
git diff --staged
git diff --stat
git diff -- README.md
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-diff).
