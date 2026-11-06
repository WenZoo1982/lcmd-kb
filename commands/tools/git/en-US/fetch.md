+++
summary = "Download updates from a remote without integrating them."
+++
---

## Purpose

Use this to inspect remote changes before deciding whether to merge or rebase.

## Basic syntax

```bash
git fetch <remote>
git fetch --all
```

## Common options

- `--all`: Fetch from all remotes.
- `--prune`: Remove stale remote-tracking references.
- `--tags`: Fetch tags as well.

## Common examples

```bash
git fetch origin
git fetch --all --prune
git log --oneline HEAD..origin/main
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-fetch).
