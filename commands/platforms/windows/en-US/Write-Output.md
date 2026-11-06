+++
summary = "Write objects to the success output stream for pipeline processing."
+++
---

## Purpose

Write objects to the success output stream for pipeline processing.

## Basic syntax

```powershell
Write-Output [-InputObject] OBJECT [OPTIONS]
```

## Common parameters

- `-NoEnumerate`: Do not enumerate collection elements.

## Common examples

```powershell
Write-Output 'Hello'
1..3 | ForEach-Object { Write-Output $_ }
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Write-Output -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/write-output/) for the complete syntax.
