+++
summary = "Export objects to a PowerShell CLIXML file."
+++
---

## Purpose

Export objects to a PowerShell CLIXML file.

## Basic syntax

```powershell
OBJECT | Export-Clixml [-Path] FILE [OPTIONS]
```

## Common parameters

- `-Path`: Specify the output file.
- `-Depth`: Set serialization depth.
- `-Encoding`: Set encoding where supported.

## Common examples

```powershell
Get-Process | Select-Object -First 5 | Export-Clixml .\processes.xml
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Export-Clixml -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/export-clixml/) for the complete syntax.
