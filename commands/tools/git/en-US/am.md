+++
summary = "Apply patches received in mailbox format."
+++
---

## Purpose

Use this in email-based workflows to apply patches sent by another contributor.

## Basic syntax

```bash
git am <patch-file>
git am < patch-file
```

## Common options

- `-3`: Try a three-way merge if a patch cannot be applied directly.
- `--abort`: Stop the current patch application.
- `--continue`: Continue after resolving conflicts.

## Common examples

```bash
git am 0001-fix.patch
git am --abort
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-am).
