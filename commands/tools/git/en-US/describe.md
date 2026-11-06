+++
summary = "Give a commit a human-readable name based on nearby tags."
+++
---

## Purpose

Use this to identify a build or revision relative to the latest reachable tag.

## Basic syntax

```bash
git describe
git describe --tags
```

## Common options

- `--tags`: Include lightweight tags.
- `--always`: Show an abbreviated commit ID when no tag is available.
- `--dirty`: Mark the result when the working tree has changes.

## Common examples

```bash
git describe --tags
git describe --tags --dirty
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-describe).
