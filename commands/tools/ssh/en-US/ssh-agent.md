+++
summary = "Run a background agent that holds unlocked private keys so later SSH connections can use them without repeatedly prompting for the key passphrase."
+++
---

## Purpose

Run a background agent that holds unlocked private keys so later SSH connections can use them without repeatedly prompting for the key passphrase.

## Basic syntax

```bash
ssh-agent [选项] [命令 [参数...]]
```

## Common options

- `-s`: Print environment setup for a Bourne-compatible shell.
- `-c`: Print environment setup for a C shell.
- `-k`: Stop the agent identified by the current agent environment.

## Common examples

```bash
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_ed25519
ssh-add -l
ssh-agent -k
```

## Usage notes

On Windows, the OpenSSH Authentication Agent is commonly managed as a Windows service. Linux and macOS usage depends on the shell environment.

## More options

This page covers high-frequency, practical options only. For the complete option list and details, see the [OpenSSH official manuals](https://www.openssh.com/manual.html) or the manual page provided by your operating system.
