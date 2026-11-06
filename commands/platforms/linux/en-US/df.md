+++
summary = "Report filesystem disk space."
+++
---

## Purpose

Report filesystem disk space. Available on Debian, Ubuntu, and Linux Mint.

## Syntax

`df [选项] [路径...]`

## Common options

- -h：易读单位
- -T：显示文件系统类型
- -i：查看 inode

## Examples

```bash
df -hT
```

## More options

See `man df` or `df --help` (if supported) for additional options.
