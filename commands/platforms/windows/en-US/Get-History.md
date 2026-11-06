+++
summary = "Get command history for the current PowerShell session."
+++
---

## Purpose

Get command history for the current PowerShell session.

## Basic syntax

```powershell
Get-History [OPTIONS]
```

## Common parameters

- `-Count`: Limit the number of entries.
- `-Id`: Select history entries by ID.

## Common examples

```powershell
Get-History
Get-History -Count 20
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Get-History -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-history/) for the complete syntax.
