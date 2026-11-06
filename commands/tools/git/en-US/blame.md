+++
summary = "Show who last changed each line of a file."
+++
---

## Purpose

Use this to trace the origin of a line and find the commit that last modified it.

## Basic syntax

```bash
git blame <file>
git blame -L <start>,<end> <file>
```

## Common options

- `-L`: Show only a selected line range.
- `-w`: Ignore whitespace changes.
- `-e`: Show author email addresses.

## Common examples

```bash
git blame src/main.py
git blame -L 20,40 README.md
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-blame).
