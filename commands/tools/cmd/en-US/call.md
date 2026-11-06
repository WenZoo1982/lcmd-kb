+++
summary = "Call another batch script and continue after it returns."
+++
---

## Purpose

Call another batch script and continue after it returns.

## Syntax

```cmd
call [script] [arguments]
```

## Common options

Commonly used between .bat/.cmd scripts; use call :label to call a batch label.

## Examples

```cmd
call build.cmd
```

## Usage notes

Command type: CMD built-in. Run it in CMD. Some operations require elevation. Verify targets and side effects before deleting, overwriting, or performing system maintenance.

## More options

Run `call /?` to see the full syntax and options available on the current Windows version.
