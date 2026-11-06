+++
summary = "Create file links."
+++
---

## Purpose

Create file links. Available on Debian, Ubuntu, and Linux Mint.

## Syntax

`ln [选项] 目标 链接名`

## Common options

- -s：创建符号链接
- -f：覆盖已有链接

## Examples

```bash
ln -s /var/log/syslog syslog
```

## More options

See `man ln` or `ln --help` (if supported) for additional options.
