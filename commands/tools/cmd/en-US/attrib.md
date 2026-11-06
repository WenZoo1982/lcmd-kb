+++
summary = "Display or change file and directory attributes."
+++
---

## Purpose

Display or change file and directory attributes.

## Syntax

```cmd
attrib [+attribute|-attribute] [path] [/s] [/d]
```

## Common options

R read-only; H hidden; S system; /s recurse; /d include directories.

## Examples

```cmd
attrib +h private.txt
```

## Usage notes

Command type: CMD external utility. Run it in CMD. Some operations require elevation. Verify targets and side effects before deleting, overwriting, or performing system maintenance.

## More options

Run `attrib /?` to see the full syntax and options available on the current Windows version.
