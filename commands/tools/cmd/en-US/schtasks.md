+++
summary = "Create, query, run, or manage Windows scheduled tasks."
+++
---

## Purpose

Create, query, run, or manage Windows scheduled tasks.

## Syntax

```cmd
schtasks /operation [options]
```

## Common options

/query list tasks; /create create a task; /run start it now; /end stop it; /delete remove it. Creating or managing tasks may require elevation.

## Examples

```cmd
schtasks /query /fo LIST /v
```

## Usage notes

Command type: Windows system utility. Run it in CMD. Some operations require elevation. Verify targets and side effects before deleting, overwriting, or performing system maintenance.

## More options

Run `schtasks /?` to see the full syntax and options available on the current Windows version.
