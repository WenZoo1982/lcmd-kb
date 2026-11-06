+++
summary = "Install a local public key in a remote account's authorized_keys file so you can authenticate with that key later."
+++
---

## Purpose

Install a local public key in a remote account's authorized_keys file so you can authenticate with that key later.

## Basic syntax

```bash
ssh-copy-id [选项] [用户@]主机
```

## Common options

- `-i file`: Select the public key file to install.
- `-p port`: Set the remote SSH port.
- `-n`: Show what would be done without installing the key.
- `-f`: Force installation without checking whether the key is already present.

## Common examples

```bash
ssh-copy-id user@example.com
ssh-copy-id -i ~/.ssh/id_ed25519.pub user@example.com
ssh-copy-id -p 2222 user@example.com
ssh-copy-id -n user@example.com
```

## Usage notes

This utility is not included in every OpenSSH installation. Windows' built-in OpenSSH usually does not provide it; public keys can be installed manually.

## More options

This page covers high-frequency, practical options only. For the complete option list and details, see the [OpenSSH official manuals](https://www.openssh.com/manual.html) or the manual page provided by your operating system.
