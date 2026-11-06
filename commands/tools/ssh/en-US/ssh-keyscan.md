+++
summary = "Collect public host keys from remote SSH servers."
+++
---

## Purpose

Collect public host keys from remote SSH servers. It is often used to prepare known_hosts files or obtain fingerprints for verification.

## Basic syntax

```bash
ssh-keyscan [选项] 主机...
```

## Common options

- `-p port`: Set the SSH server port.
- `-t type`: Select key types such as ed25519 or rsa.
- `-H`: Hash host names in the output.
- `-f file`: Read host names from a file.
- `-4` / `-6`: Use IPv4 / IPv6 only.

## Common examples

```bash
ssh-keyscan example.com
ssh-keyscan -p 2222 -t ed25519 example.com
ssh-keyscan example.com >> ~/.ssh/known_hosts
ssh-keyscan -H example.com >> ~/.ssh/known_hosts
```

## Usage notes

Keys collected by ssh-keyscan do not prove server identity. Verify fingerprints through a trusted channel before trusting or installing them.

## More options

This page covers high-frequency, practical options only. For the complete option list and details, see the [OpenSSH official manuals](https://www.openssh.com/manual.html) or the manual page provided by your operating system.
