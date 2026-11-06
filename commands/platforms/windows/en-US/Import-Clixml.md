+++
summary = "Import serialized objects from a CLIXML file."
+++
---

## Purpose

Import serialized objects from a CLIXML file.

## Basic syntax

```powershell
Import-Clixml [-Path] FILE
```

## Common parameters

- `-Path`: Specify the CLIXML file path.

## Common examples

```powershell
$items = Import-Clixml .\processes.xml
$items
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Import-Clixml -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/import-clixml/) for the complete syntax.
