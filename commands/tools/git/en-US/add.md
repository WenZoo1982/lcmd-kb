+++
summary = "Stage file changes for the next commit."
+++
---

## Purpose

Use this when you want selected changes to be included in your next commit.

## Basic syntax

```bash
git add <file-or-directory>
git add -p <file>
```

## Common options

- `.`: Stage changes under the current directory.
- `-A`: Stage all additions, modifications, and deletions.
- `-p`: Select individual change hunks interactively.

## Common examples

```bash
git add README.md
git add .
git add -p src/main.py
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-add).
