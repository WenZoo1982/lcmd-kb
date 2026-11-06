+++
summary = "Manage another Git repository embedded in this repository."
+++
---

## Purpose

Use this when a project depends on a separate repository and needs to pin a specific revision of it.

## Basic syntax

```bash
git submodule add <repository-url> <directory>
git submodule update --init --recursive
```

## Common options

- `add`: Add a submodule.
- `update --init`: Initialize and check out submodules.
- `--recursive`: Also process nested submodules.
- `status`: Show submodule state.

## Common examples

```bash
git submodule add https://github.com/user/lib.git libs/lib
git submodule update --init --recursive
git submodule status
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-submodule).
