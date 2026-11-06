+++
summary = "Get PowerShell drives."
+++
---

## Purpose

Get PowerShell drives.

## Basic syntax

```powershell
Get-PSDrive [NAME] [OPTIONS]
```

## Common parameters

- `-Name`: Filter by drive name.
- `-PSProvider`: Filter by provider.
- `-Scope`: Select a scope.

## Common examples

```powershell
Get-PSDrive
Get-PSDrive -PSProvider FileSystem
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Get-PSDrive -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-psdrive/) for the complete syntax.
