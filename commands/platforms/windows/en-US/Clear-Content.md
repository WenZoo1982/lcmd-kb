+++
summary = "Clear the contents of an item without deleting the item itself."
+++
---

## Purpose

Clear the contents of an item without deleting the item itself.

## Basic syntax

```powershell
Clear-Content [-Path] PATH [OPTIONS]
```

## Common parameters

- `-Force`: Clear restricted items where supported.
- `-WhatIf`: Preview the operation.

## Common examples

```powershell
Clear-Content .\app.log
Clear-Content .\*.tmp -WhatIf
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Clear-Content -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/clear-content/) for the complete syntax.
