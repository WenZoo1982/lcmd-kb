+++
summary = "Compare two sets of objects and show their differences."
+++
---

## Purpose

Compare two sets of objects and show their differences.

## Basic syntax

```powershell
Compare-Object [-ReferenceObject] REFERENCE [-DifferenceObject] DIFFERENCE [OPTIONS]
```

## Common parameters

- `-Property`: Select properties to compare.
- `-IncludeEqual`: Include matching items.
- `-PassThru`: Return original objects.
- `-SyncWindow`: Set the comparison window.

## Common examples

```powershell
Compare-Object (Get-Content .\old.txt) (Get-Content .\new.txt)
Compare-Object $a $b -Property Name,Version
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Compare-Object -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/compare-object/) for the complete syntax.
