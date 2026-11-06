+++
summary = "Clean up and optimize repository data."
+++
---

## Purpose

Git usually runs maintenance automatically. Manual use is rarely needed.

## Basic syntax

```bash
git gc
```

## Common options

- `--prune=<time>`: Prune unreachable objects older than the given time.
- `--aggressive`: Perform more thorough but slower optimization; not recommended for routine use.

## Common examples

```bash
git gc
git gc --prune=now
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-gc).
