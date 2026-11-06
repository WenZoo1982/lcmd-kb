+++
summary = "Export commits as patch files."
+++
---

## Purpose

Use this to share changes through email or a patch-based review workflow.

## Basic syntax

```bash
git format-patch <range-or-commit>
```

## Common options

- `-1`: Export only the latest commit.
- `-o <directory>`: Choose an output directory.
- `--stdout`: Write the patch to standard output.

## Common examples

```bash
git format-patch -1 HEAD
git format-patch -o patches origin/main..HEAD
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-format-patch).
