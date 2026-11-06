+++
summary = "Switch branches or create and switch to a new branch."
+++
---

## Purpose

Use this for everyday branch switching. Prefer it over the legacy `checkout` command.

## Basic syntax

```bash
git switch <branch>
git switch -c <new-branch>
```

## Common options

- `-c`: Create and switch to a new branch.
- `-`: Switch to the previously checked-out branch.
- `--detach`: Check out a commit without being on a branch.

## Common examples

```bash
git switch main
git switch -c feature/login
git switch -
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-switch).
