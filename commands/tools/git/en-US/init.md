+++
summary = "Create a new local Git repository in the current or specified directory."
+++

## Purpose

Initialize a directory as a Git repository so Git can track its changes.

## Basic syntax

```bash
git init [directory]
```

## Common options

| Goal | Command | Description |
|---|---|---|
| Initialize the current directory | `git init` | Create a repository here |
| Initialize a named directory | `git init my-project` | Create the directory and initialize it |

## Common examples

```bash
cd my-project
git init
```

## Notes

`git init` creates a local repository. It does not create a remote repository or commit files.
