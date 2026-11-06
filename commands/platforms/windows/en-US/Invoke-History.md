+++
summary = "Run a command from the current session history."
+++
---

## Purpose

Run a command from the current session history.

## Basic syntax

```powershell
Invoke-History [[-Id] ID_OR_RANGE]
```

## Common parameters

- `-Id`: Specify a history ID or range.

## Common examples

```powershell
Get-History
Invoke-History -Id 12
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Invoke-History -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/invoke-history/) for the complete syntax.
