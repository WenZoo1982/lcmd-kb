+++
summary = "Export objects to a CSV file."
+++
---

## Purpose

Export objects to a CSV file.

## Basic syntax

```powershell
OBJECT | Export-Csv [-Path] FILE [OPTIONS]
```

## Common parameters

- `-NoTypeInformation`: Omit type information; commonly used in Windows PowerShell.
- `-Delimiter`: Specify a delimiter.
- `-Append`: Append to an existing file.
- `-Encoding`: Specify encoding.

## Common examples

```powershell
Get-Process | Select-Object Name,Id,CPU | Export-Csv .\processes.csv -NoTypeInformation -Encoding UTF8
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Export-Csv -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/export-csv/) for the complete syntax.
