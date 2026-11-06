+++
summary = "List references available in a remote repository."
+++
---

## Purpose

Use this to check remote branches or tags without cloning the repository.

## Basic syntax

```bash
git ls-remote <repository-url>
```

## Common options

- `--heads`: Show branches only.
- `--tags`: Show tags only.

## Common examples

```bash
git ls-remote --heads origin
git ls-remote --tags origin
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-ls-remote).
