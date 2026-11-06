+++
summary = "Group objects based on property values."
+++
---

## Purpose

Group objects based on property values.

## Basic syntax

```powershell
OBJECT | Group-Object [-Property] PROPERTY [OPTIONS]
```

## Common parameters

- `-NoElement`: Do not include grouped objects.
- `-AsHashTable`: Return a hashtable.
- `-CaseSensitive`: Group case-sensitively.

## Common examples

```powershell
Get-Process | Group-Object ProcessName
Get-ChildItem | Group-Object Extension
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Group-Object -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/group-object/) for the complete syntax.
