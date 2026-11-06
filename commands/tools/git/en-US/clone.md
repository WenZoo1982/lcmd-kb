+++
summary = "Copy a remote repository to your computer."
+++
---

## Purpose

Use this when you first download a project from GitHub or another Git server.

## Basic syntax

```bash
git clone <repository-url>
git clone <repository-url> <directory>
```

## Common options

- `-b <branch>`: Check out a specific branch.
- `--depth 1`: Fetch only the latest history depth.
- `--recurse-submodules`: Also initialize submodules.

## Common examples

```bash
git clone https://github.com/user/project.git
git clone -b dev https://github.com/user/project.git
git clone --depth 1 <repository-url>
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-clone).
