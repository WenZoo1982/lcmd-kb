+++
summary = "Generate random numbers or select random objects from a collection."
+++
---

## Purpose

Generate random numbers or select random objects from a collection.

## Basic syntax

```powershell
Get-Random [OPTIONS]
```

## Common parameters

- `-Minimum` / `-Maximum`: Set the numeric range.
- `-Count`: Return multiple results.
- `-InputObject`: Select from a collection.
- `-SetSeed`: Set the random seed.

## Common examples

```powershell
Get-Random -Minimum 1 -Maximum 101
Get-ChildItem | Get-Random -Count 3
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Get-Random -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-random/) for the complete syntax.
