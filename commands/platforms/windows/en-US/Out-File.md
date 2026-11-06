+++
summary = "Send pipeline output to a text file."
+++
---

## Purpose

Send pipeline output to a text file.

## Basic syntax

```powershell
OBJECT | Out-File [-FilePath] FILE [OPTIONS]
```

## Common parameters

- `-Append`: Append to the file.
- `-Encoding`: Specify encoding.
- `-Width`: Set output width.
- `-NoClobber`: Do not overwrite an existing file.

## Common examples

```powershell
Get-Process | Out-File .\processes.txt
Get-Service | Out-File .\services.txt -Append -Encoding utf8
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Out-File -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/out-file/) for the complete syntax.
