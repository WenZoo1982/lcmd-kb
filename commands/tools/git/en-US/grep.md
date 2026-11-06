+++
summary = "Search tracked files for text."
+++
---

## Purpose

Use this to find a function name, configuration key, TODO, or other text in the repository.

## Basic syntax

```bash
git grep <pattern>
```

## Common options

- `-n`: Show line numbers.
- `-i`: Ignore case.
- `-l`: Show matching file names only.
- `-e`: Specify the search pattern.

## Common examples

```bash
git grep -n "TODO"
git grep -i "timeout"
git grep "def main" -- '*.py'
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-grep).
