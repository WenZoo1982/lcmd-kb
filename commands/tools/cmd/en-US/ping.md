+++
summary = "Test network reachability and round-trip time to a host."
+++
---

## Purpose

Test network reachability and round-trip time to a host.

## Syntax

```cmd
ping [options] target
```

## Common options

-n count set the number of requests; -t ping continuously until stopped; -4 or -6 select the IP version.

## Examples

```cmd
ping -n 4 example.com
```

## Usage notes

Command type: Windows networking utility. Run it in CMD. Some operations require elevation. Verify targets and side effects before deleting, overwriting, or performing system maintenance.

## More options

Run `ping /?` to see the full syntax and options available on the current Windows version.
