+++
summary = "List directory contents and control output format or hidden-file visibility."
+++

## Purpose

List files and subdirectories in the current or a specified directory.

## Basic syntax

```bash
ls [options] [path]
```

## Common options

| Goal | Command | Description |
|---|---|---|
| List the current directory | `ls` | Show a concise listing |
| Show detailed information | `ls -l` | Include permissions, size, and timestamps |
| Include hidden files | `ls -a` | Include names beginning with a dot |
| Use readable size units | `ls -lh` | Display sizes in KB, MB, and similar units |

## Common examples

```bash
ls -lah ~/Downloads
```

Show all items in Downloads, including hidden files, with detailed information.

## Notes

Implementations can differ across Unix-like systems. Linux documentation in this knowledge base targets common GNU behavior.
