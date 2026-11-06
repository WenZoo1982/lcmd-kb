+++
summary = "List currently running processes."
+++
---

## Purpose

List currently running processes.

## Syntax

```cmd
tasklist [options]
```

## Common options

/fi filter by criteria; /fo table|list|csv choose output format; /svc show services hosted by each process.

## Examples

```cmd
tasklist /fi "imagename eq notepad.exe"
```

## Usage notes

Command type: Windows system utility. Run it in CMD. Some operations require elevation. Verify targets and side effects before deleting, overwriting, or performing system maintenance.

## More options

Run `tasklist /?` to see the full syntax and options available on the current Windows version.
