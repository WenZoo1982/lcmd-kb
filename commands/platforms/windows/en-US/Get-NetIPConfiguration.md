+++
summary = "Get IP configuration for network interfaces."
+++
---

## Purpose

Get IP configuration for network interfaces.

## Basic syntax

```powershell
Get-NetIPConfiguration [OPTIONS]
```

## Common parameters

- `-InterfaceAlias`: Filter by interface alias.
- `-All`: Include additional interfaces.
- `-Detailed`: Display detailed configuration.

## Common examples

```powershell
Get-NetIPConfiguration
Get-NetIPConfiguration -Detailed
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Get-NetIPConfiguration -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-netipconfiguration/) for the complete syntax.
