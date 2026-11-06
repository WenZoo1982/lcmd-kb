+++
summary = "Query the APT package cache."
+++
---

## Purpose

Query the APT package cache. Available on Debian, Ubuntu, and Linux Mint.

## Syntax

`apt-cache 子命令 [参数...]`

## Common options

- search：搜索
- show：显示详情
- policy：查看版本来源
- depends：查看依赖

## Examples

```bash
apt-cache policy bash
```

## More options

See `man apt-cache` or `apt-cache --help` (if supported) for additional options.
