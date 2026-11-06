+++
summary = "Change the current working location."
+++
---

## Purpose

Change the current working location.

## Basic syntax

```powershell
Set-Location [[-Path] PATH]
```

## Common parameters

- `-Path`: Specify the destination path.
- `-LiteralPath`: Treat the path literally; do not expand wildcards.
- `-PassThru`: Return the location object.

## Common examples

```powershell
Set-Location C:\Users
Set-Location ..
Set-Location Env:
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Set-Location -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/set-location/) for the complete syntax.
