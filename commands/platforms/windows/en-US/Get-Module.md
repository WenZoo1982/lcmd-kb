+++
summary = "Get loaded or available PowerShell modules."
+++
---

## Purpose

Get loaded or available PowerShell modules.

## Basic syntax

```powershell
Get-Module [NAME] [OPTIONS]
```

## Common parameters

- `-ListAvailable`: List available modules.
- `-Name`: Filter by module name.
- `-All`: Include nested modules.

## Common examples

```powershell
Get-Module
Get-Module -ListAvailable
Get-Module -ListAvailable Microsoft.PowerShell.*
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Get-Module -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-module/) for the complete syntax.
