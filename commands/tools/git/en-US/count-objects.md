+++
summary = "Show object counts and disk usage."
+++
---

## Purpose

Use this to investigate why the `.git` directory is taking up space.

## Basic syntax

```bash
git count-objects -v
```

## Common options

- `-v`: Show detailed statistics.
- `-H`: Use human-readable size units.

## Common examples

```bash
git count-objects -vH
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-count-objects).
