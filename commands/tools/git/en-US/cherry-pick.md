+++
summary = "Apply the changes from an existing commit to the current branch."
+++
---

## Purpose

Use this to bring one specific fix or change from another branch without merging the entire branch.

## Basic syntax

```bash
git cherry-pick <commit>
```

## Common options

- `-n`: Apply changes without creating a commit.
- `--continue`: Continue after resolving conflicts.
- `--abort`: Cancel the operation.

## Common examples

```bash
git switch release
git cherry-pick a1b2c3d
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-cherry-pick).
