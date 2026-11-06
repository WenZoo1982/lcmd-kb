+++
summary = "Format objects as a list of properties."
+++
---

## Purpose

Format objects as a list of properties.

## Basic syntax

```powershell
OBJECT | Format-List [PROPERTY] [OPTIONS]
```

## Common parameters

- `-Property`: Select displayed properties.
- `-Force`: Display additional available properties.
- `*`: Display all properties.

## Common examples

```powershell
Get-Process powershell | Format-List *
Get-Service Spooler | Format-List Name,Status
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Format-List -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/format-list/) for the complete syntax.
