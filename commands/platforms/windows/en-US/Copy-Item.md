+++
summary = "Copy files, directories, or other provider items."
+++
---

## Purpose

Copy files, directories, or other provider items.

## Basic syntax

```powershell
Copy-Item [-Path] SOURCE [-Destination] DESTINATION [OPTIONS]
```

## Common parameters

- `-Recurse`: Copy directories recursively.
- `-Force`: Overwrite destination items where supported.
- `-Container`: Preserve directory containers.
- `-PassThru`: Return the copied item.

## Common examples

```powershell
Copy-Item .\a.txt .\Backup\
Copy-Item .\Project .\Backup -Recurse
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Copy-Item -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/copy-item/) for the complete syntax.
