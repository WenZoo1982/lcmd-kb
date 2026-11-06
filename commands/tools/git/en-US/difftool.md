+++
summary = "Compare changes with an external visual diff tool."
+++
---

## Purpose

Use this when you prefer a graphical comparison over terminal output.

## Basic syntax

```bash
git difftool [comparison]
```

## Common options

- `--tool=<tool>`: Select a configured diff tool.
- `--dir-diff`: Compare directories.
- `--no-prompt`: Do not ask before launching each comparison.

## Common examples

```bash
git difftool
git difftool --staged
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-difftool).
