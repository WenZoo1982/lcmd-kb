+++
summary = "Remove a directory; rmdir is an equivalent command."
+++
---

## Purpose

Remove a directory; rmdir is an equivalent command.

## Syntax

```cmd
rd [/s] [/q] [path]
```

## Common options

/s remove the directory tree; /q quiet mode. Verify the target path before using /s.

## Examples

```cmd
rd /s D:\Work\OldBuild
```

## Usage notes

Command type: CMD built-in. Run it in CMD. Some operations require elevation. Verify targets and side effects before deleting, overwriting, or performing system maintenance.

## More options

Run `rd /?` to see the full syntax and options available on the current Windows version.
