+++
summary = "Copy files between local and remote hosts over SSH."
+++
---

## Purpose

Copy files between local and remote hosts over SSH. It is useful for quick uploads and downloads, including directories.

## Basic syntax

```bash
scp [选项] 源路径 目标路径
```

## Common options

- `-P port`: Set the remote SSH port (uppercase P).
- `-i file`: Select a private key file.
- `-r`: Copy directories recursively.
- `-p`: Preserve modification/access times and file mode.
- `-C`: Enable compression.
- `-J host`: Connect through a jump host.

## Common examples

```bash
scp report.txt user@example.com:/home/user/
scp user@example.com:/var/log/app.log .
scp -r ./website user@example.com:/var/www/
scp -P 2222 backup.zip user@example.com:/data/
```

## Usage notes

Recent OpenSSH versions use the SFTP protocol for scp by default; older versions may behave differently. Check destination paths and overwrite risks.

## More options

This page covers high-frequency, practical options only. For the complete option list and details, see the [OpenSSH official manuals](https://www.openssh.com/manual.html) or the manual page provided by your operating system.
