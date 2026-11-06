+++
summary = "Find files and directories."
+++
---

## Purpose

Find files and directories. Available on Debian, Ubuntu, and Linux Mint.

## Syntax

`find [路径] [条件] [动作]`

## Common options

- -name：按名称匹配
- -type：按类型筛选
- -mtime：按修改时间筛选

## Examples

```bash
find . -type f -name '*.log'
```

## More options

See `man find` or `find --help` (if supported) for additional options.
