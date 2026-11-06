+++
summary = "Find the commit that introduced a bug by binary search."
+++
---

## Purpose

Use this when you know one revision works and a later revision is broken.

## Basic syntax

```bash
git bisect start
git bisect bad [revision]
git bisect good <known-good-revision>
```

## Common options

- `start`: Begin the search.
- `bad`: Mark a revision as broken.
- `good`: Mark a revision as working.
- `reset`: End the search and return to the original state.

## Common examples

```bash
git bisect start
git bisect bad
git bisect good v1.2.0
# Test each revision and mark it good or bad as prompted
git bisect reset
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-bisect).
