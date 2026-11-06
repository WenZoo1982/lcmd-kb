+++
summary = "Display network connections, listening ports, and protocol statistics."
+++
---

## Purpose

Display network connections, listening ports, and protocol statistics.

## Syntax

```cmd
netstat [options]
```

## Common options

-a show all connections and listening ports; -n use numeric addresses and ports; -o show PID; -b show the associated executable (may require elevation).

## Examples

```cmd
netstat -ano
```

## Usage notes

Command type: Windows networking utility. Run it in CMD. Some operations require elevation. Verify targets and side effects before deleting, overwriting, or performing system maintenance.

## More options

Run `netstat /?` to see the full syntax and options available on the current Windows version.
