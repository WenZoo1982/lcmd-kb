+++
summary = "Create or extract tar archives."
+++
---

## Purpose

Create or extract tar archives. Available on Debian, Ubuntu, and Linux Mint.

## Syntax

`tar [选项] 归档文件 [文件...]`

## Common options

- -c：创建
- -x：解压
- -t：列出
- -f：指定归档
- -z：gzip

## Examples

```bash
tar -czf backup.tar.gz project/
```

## More options

See `man tar` or `tar --help` (if supported) for additional options.
