+++
summary = "Check out only selected parts of a repository."
+++
---

## Purpose

Use this for a large repository when you need only a few directories in your working tree.

## Basic syntax

```bash
git sparse-checkout init --cone
git sparse-checkout set <directories>
```

## Common options

- `init --cone`: Enable cone mode, suitable for most directory-based use.
- `set`: Choose directories to check out.
- `disable`: Turn sparse checkout off.

## Common examples

```bash
git sparse-checkout init --cone
git sparse-checkout set src docs
git sparse-checkout disable
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-sparse-checkout).
