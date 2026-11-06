+++
summary = "Summarize commits by author."
+++
---

## Purpose

Use this to quickly see contributors and their commit counts.

## Basic syntax

```bash
git shortlog
```

## Common options

- `-s`: Show only counts and author names.
- `-n`: Sort by commit count.
- `-e`: Include email addresses.

## Common examples

```bash
git shortlog -sn
git shortlog -sne
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-shortlog).
