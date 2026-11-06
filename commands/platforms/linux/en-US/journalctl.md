+++
summary = "Query the systemd journal."
+++
---

## Purpose

Query the systemd journal. Available on Debian, Ubuntu, and Linux Mint.

## Syntax

`journalctl [选项]`

## Common options

- -u：按单元筛选
- -b：本次启动
- -n：最近行数
- -f：持续跟踪

## Examples

```bash
journalctl -u ssh -n 50
```

## More options

See `man journalctl` or `journalctl --help` (if supported) for additional options.
