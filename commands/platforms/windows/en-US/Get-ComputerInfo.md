+++
summary = "Get consolidated operating system and computer hardware information."
+++
---

## Purpose

Get consolidated operating system and computer hardware information.

## Basic syntax

```powershell
Get-ComputerInfo [OPTIONS]
```

## Common parameters

- `-Property`: Return only selected properties.

## Common examples

```powershell
Get-ComputerInfo
Get-ComputerInfo -Property WindowsProductName,WindowsVersion,OsBuildNumber
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Get-ComputerInfo -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-computerinfo/) for the complete syntax.
