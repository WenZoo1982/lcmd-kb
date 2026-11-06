+++
summary = "List files, directories, or registry items."
+++
---

## Purpose

List files, directories, or registry items.

## Basic syntax

```powershell
Get-ChildItem [[-Path] PATH] [OPTIONS]
```

## Common parameters

- `-Force`: Include hidden and system items.
- `-Recurse`: Traverse subdirectories recursively.
- `-Filter`: Filter at the provider level.
- `-File` / `-Directory`: Return only files or directories.
- `-Name`: Return names only.

## Common examples

```powershell
Get-ChildItem C:\Windows
Get-ChildItem . -File
Get-ChildItem . -Filter *.log -Recurse
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Get-ChildItem -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-childitem/) for the complete syntax.
