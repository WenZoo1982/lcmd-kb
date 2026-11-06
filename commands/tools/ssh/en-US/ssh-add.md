+++
summary = "Add private keys to ssh-agent for authentication."
+++
---

## Purpose

Add private keys to ssh-agent for authentication. You can also list keys, inspect public keys, and remove keys from the agent.

## Basic syntax

```bash
ssh-add [选项] [私钥文件...]
```

## Common options

- `-l`: List fingerprints of keys held by the agent.
- `-L`: List public keys held by the agent.
- `-d file`: Remove the specified identity.
- `-D`: Remove all identities from the agent.
- `-t time`: Set how long an added identity remains in the agent.

## Common examples

```bash
ssh-add ~/.ssh/id_ed25519
ssh-add -l
ssh-add -L
ssh-add -t 1h ~/.ssh/id_ed25519
ssh-add -d ~/.ssh/id_ed25519
ssh-add -D
```

## Usage notes

A working ssh-agent is required. Never paste private-key contents into command arguments or chat messages.

## More options

This page covers high-frequency, practical options only. For the complete option list and details, see the [OpenSSH official manuals](https://www.openssh.com/manual.html) or the manual page provided by your operating system.
