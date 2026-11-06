+++
summary = "Clear command history for the current PowerShell session."
+++
---

## Purpose

Clear command history for the current PowerShell session.

## Basic syntax

```powershell
Clear-History [OPTIONS]
```

## Common parameters

- `-Id`: Clear a specified history ID.
- `-Count`: Clear a specified number of entries.
- `-Newest`: Select the newest entries with Count.

## Common examples

```powershell
Clear-History
Clear-History -Count 10
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Clear-History -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/clear-history/) for the complete syntax.
