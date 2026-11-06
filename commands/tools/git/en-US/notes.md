+++
summary = "Attach notes to commits without changing the commits."
+++
---

## Purpose

Use this for review notes or internal annotations that should not become part of the commit message.

## Basic syntax

```bash
git notes add -m "note" <commit>
```

## Common options

- `show`: Display notes.
- `add -m`: Add a note.
- `edit`: Edit an existing note.

## Common examples

```bash
git notes add -m "Regression tests passed" HEAD
git notes show HEAD
```

## More options

This page covers selected commonly used options only. For the complete option list and detailed explanations, see the [official Git documentation](https://git-scm.com/docs/git-notes).
