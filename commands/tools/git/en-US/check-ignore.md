+++
summary = "Find out which ignore rule excludes a path."
+++
---

## Purpose

Use this when a file does not appear in Git status and you need to know why.

## Basic syntax

```bash
git check-ignore -v <path>
```

## Common options

- `-v`: Show the matching rule and source file.
- `-n`: Show non-matching results as well.

## Common examples

```bash
git check-ignore -v build/output.tmp
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-check-ignore).
