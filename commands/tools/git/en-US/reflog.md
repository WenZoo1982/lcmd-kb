+++
summary = "Show the history of changes to HEAD and branch references."
+++
---

## Purpose

Use this to find a previous commit after an accidental reset, branch switch, or other reference movement.

## Basic syntax

```bash
git reflog
git reflog <branch>
```

## Common options

- `--all`: Show logs for all refs.
- `--date=local`: Display timestamps in local time.

## Common examples

```bash
git reflog
git reflog --date=local
# Find the target entry, then use its commit ID to recover
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-reflog).
