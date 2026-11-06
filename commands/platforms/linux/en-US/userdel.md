+++
summary = "Delete a user account."
+++
---

## Purpose

Delete a user account. Available on Debian, Ubuntu, and Linux Mint.

## Syntax

`sudo userdel [选项] 用户`

## Common options

- -r：同时删除主目录和邮件目录

## Examples

```bash
sudo userdel -r olduser
```

## More options

See `man userdel` or `userdel --help` (if supported) for additional options.
