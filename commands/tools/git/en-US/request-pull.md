+++
summary = "Generate a summary asking someone to pull a branch."
+++
---

## Purpose

Use this in email-based workflows to tell a maintainer what changes are available for integration.

## Basic syntax

```bash
git request-pull <base> <repository-url> <branch>
```

## Common options

- `<base>`: The commit the recipient already has.
- `<repository-url>`: A repository the recipient can access.
- `<branch>`: The branch containing the proposed changes.

## Common examples

```bash
git request-pull main https://github.com/user/project.git feature/login
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-request-pull).
