+++
summary = "Send a signal to a process."
+++
---

## Purpose

Send a signal to a process. Available on Debian, Ubuntu, and Linux Mint.

## Syntax

`kill [选项] PID...`

## Common options

- -TERM：请求正常终止
- -KILL：强制终止
- -l：列出信号

## Examples

```bash
kill -TERM 1234
```

## More options

See `man kill` or `kill --help` (if supported) for additional options.
