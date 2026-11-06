+++
summary = "Modify Git index entries directly."
+++
---

## Purpose

This is mainly for special index workflows and automation. Use `git add` for normal staging.

## Basic syntax

```bash
git update-index <options>
```

## Common options

- `--assume-unchanged`: Tell Git to avoid checking a file for changes; this is not a replacement for ignore rules.
- `--no-assume-unchanged`: Clear that flag.

## Common examples

```bash
git update-index --assume-unchanged local-config.ini
git update-index --no-assume-unchanged local-config.ini
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-update-index).
