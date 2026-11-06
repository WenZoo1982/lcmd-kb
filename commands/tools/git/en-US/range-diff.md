+++
summary = "Compare two versions of a commit series."
+++
---

## Purpose

Use this after editing or rebasing a series of commits to see how the new series differs from the old one.

## Basic syntax

```bash
git range-diff <old-range> <new-range>
```

## Common options

- `--creation-factor=<percent>`: Adjust how loosely commits are matched.

## Common examples

```bash
git range-diff main...feature-old main...feature-new
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-range-diff).
