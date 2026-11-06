+++
summary = "Copy files and directory trees with additional filtering options."
+++
---

## Purpose

Copy files and directory trees with additional filtering options.

## Syntax

```cmd
xcopy source [destination] [options]
```

## Common options

/e copy subdirectories including empty ones; /s omit empty directories; /i assume destination is a directory; /y suppress overwrite prompts.

## Examples

```cmd
xcopy D:\Project E:\Backup\Project /e /i /y
```

## Usage notes

Command type: External executable. Run it in CMD. Some operations require elevation. Verify targets and side effects before deleting, overwriting, or performing system maintenance.

## More options

Run `xcopy /?` to see the full syntax and options available on the current Windows version.
