+++
summary = "Move or rename files, directories, and other items."
+++
---

## Purpose

Move or rename files, directories, and other items.

## Basic syntax

```powershell
Move-Item [-Path] SOURCE [-Destination] DESTINATION [OPTIONS]
```

## Common parameters

- `-Force`: Overwrite destination items where supported.
- `-WhatIf`: Preview the move.
- `-PassThru`: Return the moved item.

## Common examples

```powershell
Move-Item .\report.txt .\Archive\
Move-Item .\old-name.txt .\new-name.txt
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Move-Item -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/move-item/) for the complete syntax.
