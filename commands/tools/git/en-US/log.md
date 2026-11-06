+++
summary = "Show the repository's commit history."
+++
---

## Purpose

Use this to find what changed, who made a change, and when it was committed.

## Basic syntax

```bash
git log
```

## Common options

- `--oneline`: Show each commit on one line.
- `--graph`: Draw a text graph of branch history.
- `--all`: Include commits reachable from all refs.
- `-n <count>`: Limit the number of commits.

## Common examples

```bash
git log --oneline -5
git log --oneline --graph --all
git log -- README.md
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-log).
