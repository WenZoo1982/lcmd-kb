+++
summary = "Check a volume's file system and report its status; repair options may require elevation."
+++
---

## Purpose

Check a volume's file system and report its status; repair options may require elevation.

## Syntax

```cmd
chkdsk [volume:] [options]
```

## Common options

/f fix errors; /scan run an online NTFS scan; /r locate bad sectors and recover readable information (can take a long time).

## Examples

```cmd
chkdsk C: /scan
```

## Usage notes

Command type: Windows system utility. Run it in CMD. Some operations require elevation. Verify targets and side effects before deleting, overwriting, or performing system maintenance.

## More options

Run `chkdsk /?` to see the full syntax and options available on the current Windows version.
