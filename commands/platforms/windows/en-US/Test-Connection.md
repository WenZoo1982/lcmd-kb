+++
summary = "Send ICMP echo requests to test network connectivity."
+++
---

## Purpose

Send ICMP echo requests to test network connectivity.

## Basic syntax

```powershell
Test-Connection [-TargetName] HOST [OPTIONS]
```

## Common parameters

- `-Count`: Specify the number of requests.
- `-Quiet`: Return a Boolean result only.
- `-IPv4` / `-IPv6`: Select the IP protocol version.
- `-TimeoutSeconds`: Set a timeout where supported.

## Common examples

```powershell
Test-Connection example.com -Count 4
Test-Connection 192.168.1.1 -Quiet
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Test-Connection -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/test-connection/) for the complete syntax.
