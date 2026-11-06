+++
summary = "Terminate one or more processes."
+++
---

## Purpose

Terminate one or more processes.

## Syntax

```cmd
taskkill [options]
```

## Common options

/pid specify a process ID; /im specify an image name; /f force termination; /t also terminate child processes.

## Examples

```cmd
taskkill /im notepad.exe
```

## Usage notes

Command type: Windows system utility. Run it in CMD. Some operations require elevation. Verify targets and side effects before deleting, overwriting, or performing system maintenance.

## More options

Run `taskkill /?` to see the full syntax and options available on the current Windows version.
