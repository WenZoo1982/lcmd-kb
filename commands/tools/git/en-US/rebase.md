+++
summary = "Replay commits on top of a different base commit."
+++
---

## Purpose

Use this to update a feature branch or organize local commits. Avoid rebasing commits that have already been shared with others.

## Basic syntax

```bash
git rebase <upstream>
git rebase -i <base>
```

## Common options

- `-i`: Interactively edit, reorder, squash, or reword commits.
- `--continue`: Continue after resolving conflicts.
- `--abort`: Cancel the rebase and restore the previous state.
- `--skip`: Skip the current commit.

## Common examples

```bash
git fetch origin
git rebase origin/main
git rebase -i HEAD~3
git rebase --abort
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-rebase).
