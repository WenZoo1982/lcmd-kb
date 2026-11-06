+++
summary = "Search for a text string in files or input."
+++
---

## Purpose

Search for a text string in files or input.

## Syntax

```cmd
find [options] "string" [file]
```

## Common options

/i ignore case; /n show line numbers; /v show non-matching lines; /c show the count of matching lines.

## Examples

```cmd
find /i "error" app.log
```

## Usage notes

Command type: CMD external utility. Run it in CMD. Some operations require elevation. Verify targets and side effects before deleting, overwriting, or performing system maintenance.

## More options

Run `find /?` to see the full syntax and options available on the current Windows version.
