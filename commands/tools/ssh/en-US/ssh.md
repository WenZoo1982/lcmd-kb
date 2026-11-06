+++
summary = "Connect to a remote host over an encrypted SSH session."
+++
---

## Purpose

Connect to a remote host over an encrypted SSH session. Use it for interactive login, remote command execution, and port forwarding.

## Basic syntax

```bash
ssh [选项] [用户@]主机 [远程命令]
```

## Common options

- `-p port`: Set the remote port; the default is 22.
- `-i file`: Select a private key file.
- `-J host`: Connect through a jump host.
- `-L local-port:target-host:target-port`: Create local port forwarding.
- `-N`: Do not run a remote command; useful for tunnels.
- `-v`: Print connection debugging information.
- `-o option=value`: Set a connection option for this invocation.

## Common examples

```bash
ssh user@192.168.1.10
ssh -p 2222 -i ~/.ssh/id_ed25519 user@example.com
ssh user@example.com "uname -a"
ssh -J jump-user@jump.example.com user@server.example.com
ssh -N -L 8080:127.0.0.1:80 user@example.com
```

## Usage notes

Verify the host fingerprint when connecting for the first time. Do not disable host-key checking just to bypass a warning.

## More options

This page covers high-frequency, practical options only. For the complete option list and details, see the [OpenSSH official manuals](https://www.openssh.com/manual.html) or the manual page provided by your operating system.
