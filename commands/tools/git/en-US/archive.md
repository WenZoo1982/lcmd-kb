+++
summary = "Export files from a repository revision."
+++
---

## Purpose

Create a source archive without including the repository's `.git` history.

## Basic syntax

```bash
git archive --format=<format> --output=<archive> <revision>
```

## Common options

- `--format=zip`: Create a ZIP archive.
- `--format=tar`: Create a TAR archive.
- `--prefix=<directory>/`: Add a directory prefix inside the archive.

## Common examples

```bash
git archive --format=zip --output=source.zip HEAD
git archive --format=tar --prefix=project/ -o source.tar HEAD
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-archive).
