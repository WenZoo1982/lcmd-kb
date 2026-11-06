+++
summary = "Show Git attributes applied to a path."
+++
---

## Purpose

Use this to troubleshoot line endings, text handling, or diff behavior.

## Basic syntax

```bash
git check-attr <attribute> -- <path>
```

## Common options

- `--all`: Show all attributes for the path.

## Common examples

```bash
git check-attr --all -- README.md
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-check-attr).
