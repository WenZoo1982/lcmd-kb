+++
summary = "Compare two files and display their differences."
+++
---

## Purpose

Compare two files and display their differences.

## Syntax

```cmd
fc [options] file1 file2
```

## Common options

/b binary comparison; /n show line numbers in text comparisons; /c ignore case.

## Examples

```cmd
fc /n old.txt new.txt
```

## Usage notes

Command type: CMD external utility. Run it in CMD. Some operations require elevation. Verify targets and side effects before deleting, overwriting, or performing system maintenance.

## More options

Run `fc /?` to see the full syntax and options available on the current Windows version.
