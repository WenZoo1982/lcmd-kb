+++
summary = "Display, set, or remove environment variables in the current CMD session."
+++
---

## Purpose

Display, set, or remove environment variables in the current CMD session.

## Syntax

```cmd
set [variable[=value]]
```

## Common options

set alone lists variables; set NAME=value sets one; set NAME= removes one. Changes normally affect only the current CMD process and its child processes.

## Examples

```cmd
set PATH
```

## Usage notes

Command type: CMD built-in. Run it in CMD. Some operations require elevation. Verify targets and side effects before deleting, overwriting, or performing system maintenance.

## More options

Run `set /?` to see the full syntax and options available on the current Windows version.
