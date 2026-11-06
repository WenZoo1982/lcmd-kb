+++
summary = "Get IP address configuration on network interfaces."
+++
---

## Purpose

Get IP address configuration on network interfaces.

## Basic syntax

```powershell
Get-NetIPAddress [OPTIONS]
```

## Common parameters

- `-AddressFamily`: Filter IPv4 or IPv6.
- `-InterfaceAlias`: Select a network interface.
- `-IPAddress`: Filter by address.

## Common examples

```powershell
Get-NetIPAddress
Get-NetIPAddress -AddressFamily IPv4
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Get-NetIPAddress -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-netipaddress/) for the complete syntax.
