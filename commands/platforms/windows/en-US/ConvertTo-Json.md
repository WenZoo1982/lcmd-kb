+++
summary = "Convert an object to a JSON-formatted string."
+++
---

## Purpose

Convert an object to a JSON-formatted string.

## Basic syntax

```powershell
OBJECT | ConvertTo-Json [OPTIONS]
```

## Common parameters

- `-Depth`: Set the serialization depth.
- `-Compress`: Remove formatting whitespace.
- `-AsArray`: Always emit a JSON array (PowerShell 7+).

## Common examples

```powershell
$data = Get-Process | Select-Object -First 2 Name,Id
$data | ConvertTo-Json -Depth 3
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help ConvertTo-Json -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/convertto-json/) for the complete syntax.
