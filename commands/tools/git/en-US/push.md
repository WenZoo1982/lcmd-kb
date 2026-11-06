+++
summary = "Upload local commits to a remote repository."
+++
---

## Purpose

Use this to publish your local commits to GitHub or another Git server.

## Basic syntax

```bash
git push <remote> <branch>
```

## Common options

- `-u`: Set the upstream branch so later pushes can usually use `git push`.
- `--all`: Push all local branches.
- `--tags`: Push all tags.
- `--force-with-lease`: Force-update a remote ref only if it still has the expected value; it can still rewrite shared history.

## Common examples

```bash
git push -u origin main
git push
git push origin --tags
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-push).
