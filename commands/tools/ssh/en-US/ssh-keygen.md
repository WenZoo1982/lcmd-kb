+++
summary = "Generate, manage, and inspect SSH keys."
+++
---

## Purpose

Generate, manage, and inspect SSH keys. Key pairs are used for public-key authentication and can also be used for server host keys.

## Basic syntax

```bash
ssh-keygen [选项]
```

## Common options

- `-t ed25519`: Generate an Ed25519 key, a good default for new user keys.
- `-C comment`: Add a descriptive comment.
- `-f file`: Choose the key file path.
- `-a number`: Set the passphrase KDF work factor.
- `-p`: Change the passphrase of an existing private key.
- `-l -f file`: Display a key fingerprint.
- `-R host`: Remove a host entry from known_hosts.

## Common examples

```bash
ssh-keygen -t ed25519 -C "my-laptop"
ssh-keygen -t ed25519 -f ~/.ssh/server_key
ssh-keygen -p -f ~/.ssh/id_ed25519
ssh-keygen -lf ~/.ssh/id_ed25519.pub
ssh-keygen -R example.com
```

## Usage notes

Keep private keys secret. In normal user authentication, deploy only the matching `.pub` public key to the remote host.

## More options

This page covers high-frequency, practical options only. For the complete option list and details, see the [OpenSSH official manuals](https://www.openssh.com/manual.html) or the manual page provided by your operating system.
