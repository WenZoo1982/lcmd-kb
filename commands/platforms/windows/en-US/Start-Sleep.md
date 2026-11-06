+++
summary = "Suspend script execution for a specified interval."
+++
---

## Purpose

Suspend script execution for a specified interval.

## Basic syntax

```powershell
Start-Sleep [-Seconds SECONDS] or [-Milliseconds MILLISECONDS]
```

## Common parameters

- `-Seconds`: Sleep for a number of seconds.
- `-Milliseconds`: Sleep for a number of milliseconds.

## Common examples

```powershell
Start-Sleep -Seconds 3
Start-Sleep -Milliseconds 500
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Start-Sleep -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/start-sleep/) for the complete syntax.
