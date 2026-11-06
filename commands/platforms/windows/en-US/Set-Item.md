+++
summary = "Set the value of an item exposed by a PowerShell provider."
+++
---

## Purpose

Set the value of an item exposed by a PowerShell provider.

## Basic syntax

```powershell
Set-Item [-Path] PATH [-Value] VALUE [OPTIONS]
```

## Common parameters

- `-Path`: Specify the item path.
- `-Value`: Set the new value.
- `-Force`: Override restricted items where supported.

## Common examples

```powershell
Set-Item Env:APP_MODE 'Production'
Get-Item Env:APP_MODE
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Set-Item -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/set-item/) for the complete syntax.
