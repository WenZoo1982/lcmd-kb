+++
summary = "Sort objects by one or more properties."
+++
---

## Purpose

Sort objects by one or more properties.

## Basic syntax

```powershell
OBJECT | Sort-Object [[-Property] PROPERTY] [OPTIONS]
```

## Common parameters

- `-Descending`: Sort in descending order.
- `-Unique`: Remove duplicates.
- `-Top` / `-Bottom`: Return top or bottom items where supported.

## Common examples

```powershell
Get-Process | Sort-Object CPU -Descending
Get-ChildItem | Sort-Object Length
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Sort-Object -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/sort-object/) for the complete syntax.
