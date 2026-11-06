+++
summary = "Get a file, directory, or another provider item."
+++
---

## Purpose

Get a file, directory, or another provider item.

## Basic syntax

```powershell
Get-Item [-Path] PATH [OPTIONS]
```

## Common parameters

- `-Force`: Get hidden or restricted items.
- `-Stream`: Inspect NTFS file streams on Windows.
- `-LiteralPath`: Treat the path literally.

## Common examples

```powershell
Get-Item .\config.json
Get-Item Env:PATH
Get-Item .\file.txt -Stream *
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Get-Item -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-item/) for the complete syntax.
