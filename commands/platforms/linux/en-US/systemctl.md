+++
summary = "Control systemd services and units."
+++
---

## Purpose

Control systemd services and units. Available on Debian, Ubuntu, and Linux Mint.

## Syntax

`systemctl [选项] 子命令 [单元]`

## Common options

- status：查看状态
- start/stop/restart：控制服务
- enable/disable：设置开机启动

## Examples

```bash
sudo systemctl status ssh
```

## More options

See `man systemctl` or `systemctl --help` (if supported) for additional options.
