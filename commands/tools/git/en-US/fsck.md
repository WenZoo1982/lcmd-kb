+++
summary = "Check the integrity of repository objects."
+++
---

## Purpose

Use this to check the object database when you suspect repository corruption or missing data.

## Basic syntax

```bash
git fsck
```

## Common options

- `--full`: Perform a full check.
- `--no-reflogs`: Do not use reflog entries when checking reachability.

## Common examples

```bash
git fsck --full
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-fsck).
