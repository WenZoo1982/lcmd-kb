+++
summary = "Get network adapter properties."
+++
---

## Purpose

Get network adapter properties.

## Basic syntax

```powershell
Get-NetAdapter [OPTIONS]
```

## Common parameters

- `-Name`: Filter by adapter name.
- `-Physical`: Show physical adapters only.
- `-IncludeHidden`: Include hidden adapters.

## Common examples

```powershell
Get-NetAdapter
Get-NetAdapter -Physical
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Get-NetAdapter -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-netadapter/) for the complete syntax.
