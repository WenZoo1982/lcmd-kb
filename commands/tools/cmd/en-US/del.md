+++
summary = "Delete one or more files; it does not remove directories themselves."
+++
---

## Purpose

Delete one or more files; it does not remove directories themselves.

## Syntax

```cmd
del [options] file
```

## Common options

/p prompt before each deletion; /f force deletion of read-only files; /s recurse; /q quiet mode.

## Examples

```cmd
del /p *.tmp
```

## Usage notes

Command type: CMD built-in. Run it in CMD. Some operations require elevation. Verify targets and side effects before deleting, overwriting, or performing system maintenance.

## More options

Run `del /?` to see the full syntax and options available on the current Windows version.
