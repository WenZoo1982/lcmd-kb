+++
summary = "Show the route taken by packets to a destination host."
+++
---

## Purpose

Show the route taken by packets to a destination host.

## Syntax

```cmd
tracert [options] target
```

## Common options

/d do not resolve router names, often speeding up output; -h set the maximum hop count.

## Examples

```cmd
tracert /d example.com
```

## Usage notes

Command type: Windows networking utility. Run it in CMD. Some operations require elevation. Verify targets and side effects before deleting, overwriting, or performing system maintenance.

## More options

Run `tracert /?` to see the full syntax and options available on the current Windows version.
