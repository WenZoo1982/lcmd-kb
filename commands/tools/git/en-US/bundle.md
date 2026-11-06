+++
summary = "Package repository history into a single file."
+++
---

## Purpose

Use this to transfer Git history when a remote connection is unavailable.

## Basic syntax

```bash
git bundle create <file.bundle> <ref>
git clone <file.bundle> <directory>
```

## Common options

- `create`: Create a bundle file.
- `verify`: Check whether a bundle is valid.
- `list-heads`: List references included in the bundle.

## Common examples

```bash
git bundle create project.bundle main
git bundle verify project.bundle
git clone project.bundle project-copy
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-bundle).
