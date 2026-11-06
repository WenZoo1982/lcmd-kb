+++
summary = "Search file contents using strings or regular expressions."
+++
---

## Purpose

Search file contents using strings or regular expressions.

## Syntax

```cmd
findstr [options] "pattern" [files...]
```

## Common options

/i ignore case; /s search current directory and subdirectories; /n show line numbers; /r use regular expressions; /c: treat the following text as one search string.

## Examples

```cmd
findstr /s /i /n "failed" *.log
```

## Usage notes

Command type: CMD external utility. Run it in CMD. Some operations require elevation. Verify targets and side effects before deleting, overwriting, or performing system maintenance.

## More options

Run `findstr /?` to see the full syntax and options available on the current Windows version.
