+++
summary = "Move the current branch pointer or reset the index."
+++
---

## Purpose

Use this to unstage changes or move the current branch to an earlier commit. `--hard` discards working-tree changes and must be used carefully.

## Basic syntax

```bash
git reset [--soft | --mixed | --hard] <revision>
git reset <path>
```

## Common options

- `--soft`: Move the branch pointer but keep changes staged.
- `--mixed`: Move the pointer and unstage changes; this is the default.
- `--hard`: Reset the index and working tree to the target revision; uncommitted changes may be lost.
- `-- <path>`: Separate options from file paths.

## Common examples

```bash
# Unstage a file but keep its edits
git reset README.md

# Undo the latest commit but keep changes staged
git reset --soft HEAD~1

# Undo the latest commit and keep edits unstaged
git reset HEAD~1

# Return to the previous commit and discard local changes
git reset --hard HEAD~1
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-reset).
