+++
summary = "Run the SSH server daemon and accept encrypted remote connections."
+++
---

## Purpose

Run the SSH server daemon and accept encrypted remote connections. Routine service control is usually handled by the operating system's service manager.

## Basic syntax

```bash
sshd [选项]
```

## Common options

- `-t`: Test the configuration and host keys without starting the server.
- `-T`: Print the effective configuration.
- `-f file`: Use an alternate configuration file.
- `-p port`: Listen on the specified port.
- `-D`: Run in the foreground.
- `-e`: Send logs to standard error.

## Common examples

```bash
sudo sshd -t
sudo sshd -T
sudo sshd -t -f /etc/ssh/sshd_config
sudo sshd -D -e -p 2222
```

## Usage notes

Run `sshd -t` after configuration changes, then reload or restart the service with the OS service manager. Keep an alternative access path before closing the current remote session.

## More options

This page covers high-frequency, practical options only. For the complete option list and details, see the [OpenSSH official manuals](https://www.openssh.com/manual.html) or the manual page provided by your operating system.
