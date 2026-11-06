+++
summary = "Create a new commit that reverses an earlier commit."
+++
---

## Purpose

Use this to undo a commit that has already been pushed or shared without deleting existing history.

## Basic syntax

```bash
git revert <commit>
```

## Common options

- `--no-edit`: Use the default revert message.
- `--no-commit`: Apply the reverse changes without committing.
- `--abort`: Cancel an in-progress revert.

## Common examples

```bash
git revert a1b2c3d
git revert --no-edit HEAD
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-revert).
