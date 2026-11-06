+++
summary = "Remove files, directories, or other provider items."
+++
---

## Purpose

Remove files, directories, or other provider items.

## Basic syntax

```powershell
Remove-Item [-Path] PATH [OPTIONS]
```

## Common parameters

- `-Recurse`: Remove directory contents recursively.
- `-Force`: Attempt to remove read-only or hidden items.
- `-WhatIf`: Preview the operation.
- `-Confirm`: Prompt before performing the operation.

## Common examples

```powershell
Remove-Item .\old.txt
Remove-Item .\Temp -Recurse
Remove-Item .\Temp -Recurse -WhatIf
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Remove-Item -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/remove-item/) for the complete syntax.
