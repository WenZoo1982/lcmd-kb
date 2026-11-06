+++
summary = "Install, inspect, and remove Debian packages."
+++
---

## Purpose

Install, inspect, and remove Debian packages. Available on Debian, Ubuntu, and Linux Mint.

## Syntax

`dpkg [选项] [动作]`

## Common options

- -i：安装 deb
- -r：卸载但保留配置
- -P：连配置一起清除
- -l：列出包
- -L：列出文件

## Examples

```bash
dpkg -l 'python3*'
```

## More options

See `man dpkg` or `dpkg --help` (if supported) for additional options.
