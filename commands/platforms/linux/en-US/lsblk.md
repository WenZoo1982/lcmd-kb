+++
summary = "List block devices."
+++
---

## Purpose

List block devices. Available on Debian, Ubuntu, and Linux Mint.

## Syntax

`lsblk [选项] [设备...]`

## Common options

- -f：显示文件系统信息
- -o：选择列
- -p：显示完整设备路径

## Examples

```bash
lsblk -f
```

## More options

See `man lsblk` or `lsblk --help` (if supported) for additional options.
