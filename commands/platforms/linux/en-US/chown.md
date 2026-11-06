+++
summary = "Change file owner and group."
+++
---

## Purpose

Change file owner and group. Available on Debian, Ubuntu, and Linux Mint.

## Syntax

`chown [选项] 用户[:组] 文件...`

## Common options

- -R：递归修改
- --reference：参照另一文件的属主

## Examples

```bash
sudo chown -R user:user data/
```

## More options

See `man chown` or `chown --help` (if supported) for additional options.
