+++
summary = "Display socket and connection information."
+++
---

## Purpose

Display socket and connection information. Available on Debian, Ubuntu, and Linux Mint.

## Syntax

`ss [选项]`

## Common options

- -t：TCP
- -u：UDP
- -l：监听
- -n：不解析名称
- -p：显示进程

## Examples

```bash
ss -tulnp
```

## More options

See `man ss` or `ss --help` (if supported) for additional options.
