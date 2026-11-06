+++
summary = "Search text using patterns."
+++
---

## Purpose

Search text using patterns. Available on Debian, Ubuntu, and Linux Mint.

## Syntax

`grep [选项] 模式 [文件...]`

## Common options

- -i：忽略大小写
- -n：显示行号
- -r：递归搜索
- -v：反向匹配

## Examples

```bash
grep -in 'error' app.log
```

## More options

See `man grep` or `grep --help` (if supported) for additional options.
