+++
summary = "Rename a file, directory, or other item."
+++
---

## Purpose

Rename a file, directory, or other item.

## Basic syntax

```powershell
Rename-Item [-Path] PATH [-NewName] NEW_NAME [OPTIONS]
```

## Common parameters

- `-NewName`: Specify the new name, not a destination path.
- `-Force`: Attempt to rename restricted items.
- `-WhatIf`: Preview the operation.

## Common examples

```powershell
Rename-Item .\draft.txt final.txt
Rename-Item .\OldFolder -NewName NewFolder
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Rename-Item -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/rename-item/) for the complete syntax.
