+++
summary = "Perform an operation for each object in the pipeline."
+++
---

## Purpose

Perform an operation for each object in the pipeline.

## Basic syntax

```powershell
OBJECT | ForEach-Object { ACTION }
```

## Common parameters

- `-Process`: Script block executed for each input object.
- `-Begin` / `-End`: Run script blocks before and after processing.
- `-Parallel`: Process items in parallel (PowerShell 7+).

## Common examples

```powershell
1..5 | ForEach-Object { $_ * 2 }
Get-Process | ForEach-Object ProcessName
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help ForEach-Object -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/foreach-object/) for the complete syntax.
