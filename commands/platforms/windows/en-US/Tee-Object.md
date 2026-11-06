+++
summary = "Save pipeline data to a file or variable while passing it along."
+++
---

## Purpose

Save pipeline data to a file or variable while passing it along.

## Basic syntax

```powershell
OBJECT | Tee-Object [-FilePath] FILE or [-Variable] VARIABLE
```

## Common parameters

- `-FilePath`: Save to a file.
- `-Variable`: Save to a variable.
- `-Append`: Append to the file.

## Common examples

```powershell
Get-Process | Tee-Object -FilePath .\processes.txt | Sort-Object CPU -Descending
Get-Service | Tee-Object -Variable services | Where-Object Status -eq Running
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Tee-Object -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/tee-object/) for the complete syntax.
