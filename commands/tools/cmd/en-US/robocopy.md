+++
summary = "Robustly copy directory trees; useful for large transfers and backups."
+++
---

## Purpose

Robustly copy directory trees; useful for large transfers and backups.

## Syntax

```cmd
robocopy source destination [file] [options]
```

## Common options

/e include all subdirectories; /z restartable mode; /mt:n multithreading; /mir mirror directories (deletes extra destination files).

## Examples

```cmd
robocopy D:\Data E:\Backup\Data /e /z /mt:8
```

## Usage notes

Command type: External executable. Run it in CMD. Some operations require elevation. Verify targets and side effects before deleting, overwriting, or performing system maintenance.

## More options

Run `robocopy /?` to see the full syntax and options available on the current Windows version.
