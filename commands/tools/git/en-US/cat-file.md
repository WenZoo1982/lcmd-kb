+++
summary = "Inspect the type, size, or contents of a Git object."
+++
---

## Purpose

Use this for targeted inspection of commits, trees, or other objects. It is a lower-level diagnostic command.

## Basic syntax

```bash
git cat-file -t <object>
git cat-file -p <object>
```

## Common options

- `-t`: Show the object type.
- `-s`: Show the object size.
- `-p`: Pretty-print the object contents.

## Common examples

```bash
git cat-file -t HEAD
git cat-file -p HEAD
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-cat-file).
