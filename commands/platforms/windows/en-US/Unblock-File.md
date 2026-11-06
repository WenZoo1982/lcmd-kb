+++
summary = "Remove the download-origin blocking mark from a file."
+++
---

## Purpose

Remove the download-origin blocking mark from a file.

## Basic syntax

```powershell
Unblock-File [-Path] FILE [OPTIONS]
```

## Common parameters

- `-Path`: Specify the file.
- `-WhatIf`: Preview the operation.
- Use only for files from trusted sources that you have inspected.

## Common examples

```powershell
Unblock-File .\trusted-script.ps1
Get-Item .\trusted-script.ps1 -Stream Zone.Identifier
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Unblock-File -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/unblock-file/) for the complete syntax.
