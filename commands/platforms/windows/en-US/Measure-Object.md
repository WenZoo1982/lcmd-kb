+++
summary = "Calculate counts, sums, averages, minimums, and maximums."
+++
---

## Purpose

Calculate counts, sums, averages, minimums, and maximums.

## Basic syntax

```powershell
OBJECT | Measure-Object [OPTIONS]
```

## Common parameters

- `-Property`: Specify a numeric property.
- `-Sum`: Calculate the sum.
- `-Average`: Calculate the average.
- `-Minimum` / `-Maximum`: Calculate minimum and maximum.

## Common examples

```powershell
Get-ChildItem -File | Measure-Object
Get-Process | Measure-Object CPU -Sum -Average -Maximum
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Measure-Object -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/measure-object/) for the complete syntax.
