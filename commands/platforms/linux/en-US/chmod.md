+++
summary = "Change file permissions."
+++
---

## Purpose

Change file permissions. Available on Debian, Ubuntu, and Linux Mint.

## Syntax

`chmod [选项] 模式 文件...`

## Common options

- -R：递归修改
- 模式可用数字（如 755）或符号（如 u+x）

## Examples

```bash
chmod 755 script.sh
```

## More options

See `man chmod` or `chmod --help` (if supported) for additional options.
