+++
summary = "Read and change Git configuration."
+++
---

## Purpose

Use this to set your commit identity, default branch name, editor, and other preferences.

## Basic syntax

```bash
git config --<scope> <key> <value>
git config --<scope> --list
```

## Common options

- `--global`: Apply to your user account.
- `--local`: Apply only to the current repository.
- `--list`: List configuration values.
- `--get`: Read one configuration value.

## Common examples

```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
git config --global --list
git config --local core.autocrlf true
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-config).
