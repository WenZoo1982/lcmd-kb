+++
summary = "Import objects from a CSV file."
+++
---

## Purpose

Import objects from a CSV file.

## Basic syntax

```powershell
Import-Csv [-Path] FILE [OPTIONS]
```

## Common parameters

- `-Delimiter`: Specify a delimiter.
- `-Header`: Supply column headers.
- `-Encoding`: Specify encoding.

## Common examples

```powershell
$users = Import-Csv .\users.csv
$users | Select-Object Name,Email
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Import-Csv -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/import-csv/) for the complete syntax.
