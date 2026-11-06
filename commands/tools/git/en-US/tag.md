+++
summary = "Create, list, or delete version tags."
+++
---

## Purpose

Use tags to mark releases or other important points in project history.

## Basic syntax

```bash
git tag
git tag <tag-name>
git tag -d <tag-name>
```

## Common options

- `-a`: Create an annotated tag.
- `-m`: Add a tag message.
- `-d`: Delete a local tag.
- `--list`: List matching tags.

## Common examples

```bash
git tag
git tag -a v1.0.0 -m "Release 1.0.0"
git push origin v1.0.0
git tag -d v1.0.0
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-tag).
