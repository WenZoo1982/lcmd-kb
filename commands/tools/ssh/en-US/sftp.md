+++
summary = "Open an interactive file-transfer session over SSH."
+++
---

## Purpose

Open an interactive file-transfer session over SSH. You can browse directories, upload and download files, rename items, and remove remote files.

## Basic syntax

```bash
sftp [选项] [用户@]主机
```

## Common options

- `-P port`: Set the remote SSH port.
- `-i file`: Select a private key file.
- `-b file`: Read SFTP commands from a batch file.
- `-J host`: Connect through a jump host.

## Common examples

```bash
sftp user@example.com
# Common commands inside the session
pwd
lpwd
ls
cd /var/www
lcd ./website
put index.html
get access.log
put -r ./assets
get -r ./backup
bye
sftp -P 2222 user@example.com
```

## Usage notes

`put` uploads local files and `get` downloads remote files. `lpwd` and `lcd` operate locally; `pwd` and `cd` operate remotely.

## More options

This page covers high-frequency, practical options only. For the complete option list and details, see the [OpenSSH official manuals](https://www.openssh.com/manual.html) or the manual page provided by your operating system.
