+++
summary = "Display information directly in the console, typically for interactive messages."
+++
---

## Purpose

Display information directly in the console, typically for interactive messages.

## Basic syntax

```powershell
Write-Host [OBJECT] [OPTIONS]
```

## Common parameters

- `-ForegroundColor`: Set the foreground color.
- `-BackgroundColor`: Set the background color.
- `-NoNewline`: Do not append a newline.

## Common examples

```powershell
Write-Host 'Done' -ForegroundColor Green
Write-Host 'Working...' -NoNewline
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Write-Host -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/write-host/) for the complete syntax.
