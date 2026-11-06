+++
summary = "Write a non-terminating error to the error stream."
+++
---

## Purpose

Write a non-terminating error to the error stream.

## Basic syntax

```powershell
Write-Error [-Message] MESSAGE [OPTIONS]
```

## Common parameters

- `-Message`: Specify the error message.
- `-ErrorId`: Set an error identifier.
- `-Category`: Set the error category.
- `-ErrorAction`: Control error handling.

## Common examples

```powershell
Write-Error 'Configuration file not found'
Write-Error 'Invalid input' -ErrorAction Stop
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Write-Error -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/write-error/) for the complete syntax.
