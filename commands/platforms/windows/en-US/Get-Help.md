+++
summary = "Display help for cmdlets, functions, scripts, and concepts."
+++
---

## Purpose

Display help for cmdlets, functions, scripts, and concepts.

## Basic syntax

```powershell
Get-Help NAME [OPTIONS]
```

## Common parameters

- `-Examples`: Show examples only.
- `-Full`: Display full help.
- `-Detailed`: Display detailed help.
- `-Online`: Open online help; requires network access.

## Common examples

```powershell
Get-Help Get-Process
Get-Help Get-ChildItem -Examples
Get-Help Get-Content -Online
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Get-Help -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-help/) for the complete syntax.
