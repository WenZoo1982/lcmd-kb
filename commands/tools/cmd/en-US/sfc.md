+++
summary = "Scan and repair protected Windows system files."
+++
---

## Purpose

Scan and repair protected Windows system files.

## Syntax

```cmd
sfc [/scannow | /verifyonly]
```

## Common options

/scannow scan and attempt repairs; /verifyonly verify without repairing. Usually requires an elevated terminal.

## Examples

```cmd
sfc /scannow
```

## Usage notes

Command type: Windows system utility. Run it in CMD. Some operations require elevation. Verify targets and side effects before deleting, overwriting, or performing system maintenance.

## More options

Run `sfc /?` to see the full syntax and options available on the current Windows version.
