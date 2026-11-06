+++
summary = "Convert a JSON string into PowerShell objects."
+++
---

## Purpose

Convert a JSON string into PowerShell objects.

## Basic syntax

```powershell
JSON_STRING | ConvertFrom-Json [OPTIONS]
```

## Common parameters

- `-AsHashtable`: Convert to a hashtable where supported.
- `-NoEnumerate`: Do not enumerate array results.

## Common examples

```powershell
'{"name":"LCMD","version":"1.0"}' | ConvertFrom-Json
$data = Get-Content .\config.json -Raw | ConvertFrom-Json
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help ConvertFrom-Json -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/convertfrom-json/) for the complete syntax.
