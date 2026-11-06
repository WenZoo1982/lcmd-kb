+++
summary = "Run a command with elevated privileges."
+++
---

## Purpose

Run a command with elevated privileges. Available on Debian, Ubuntu, and Linux Mint.

## Syntax

`sudo [选项] 命令 [参数...]`

## Common options

- -u：指定运行用户
- -i：启动登录 shell
- -k：使缓存凭据失效

## Examples

```bash
sudo apt update
```

## More options

See `man sudo` or `sudo --help` (if supported) for additional options.
