+++
summary = "Create a file, directory, or another provider item."
+++
---

## Purpose

Create a file, directory, or another provider item.

## Basic syntax

```powershell
New-Item [-Path] PATH [OPTIONS]
```

## Common parameters

- `-ItemType`: Specify a type such as File or Directory.
- `-Force`: Override or create required parent items where supported.
- `-Value`: Set the item's content or value.

## Common examples

```powershell
New-Item -ItemType Directory -Path .\Logs
New-Item -ItemType File -Path .\app.log
New-Item -ItemType File -Path .\note.txt -Value 'Hello'
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help New-Item -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/new-item/) for the complete syntax.
