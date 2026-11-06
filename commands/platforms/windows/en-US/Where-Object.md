+++
summary = "Filter objects in the pipeline based on a condition."
+++
---

## Purpose

Filter objects in the pipeline based on a condition.

## Basic syntax

```powershell
OBJECT | Where-Object { CONDITION }
```

## Common parameters

- `-FilterScript`: Specify a filtering script block.
- Simplified syntax: `Where-Object PROPERTY -COMPARISON VALUE`.

## Common examples

```powershell
Get-Process | Where-Object CPU -gt 10
Get-Service | Where-Object {$_.Status -eq 'Running'}
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Where-Object -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/where-object/) for the complete syntax.
