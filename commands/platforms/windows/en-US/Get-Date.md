+++
summary = "Get the current date and time."
+++
---

## Purpose

Get the current date and time.

## Basic syntax

```powershell
Get-Date [OPTIONS]
```

## Common parameters

- `-Format`: Format using a .NET format string.
- `-UFormat`: Use a Unix-style format string.
- `-Date`: Specify a date/time value.
- `-AsUTC`: Convert to UTC where supported.

## Common examples

```powershell
Get-Date
Get-Date -Format 'yyyy-MM-dd HH:mm:ss'
(Get-Date).AddDays(7)
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Get-Date -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-date/) for the complete syntax.
