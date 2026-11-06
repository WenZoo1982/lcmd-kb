+++
summary = "Select object properties or a specified number of objects."
+++
---

## Purpose

Select object properties or a specified number of objects.

## Basic syntax

```powershell
OBJECT | Select-Object [OPTIONS]
```

## Common parameters

- `-Property`: Select properties.
- `-First` / `-Last`: Select the first or last objects.
- `-ExpandProperty`: Expand a property value.
- `-Unique`: Return unique results.

## Common examples

```powershell
Get-Process | Select-Object -First 10 Name,Id,CPU
Get-Service | Select-Object -ExpandProperty Name
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Select-Object -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/select-object/) for the complete syntax.
