+++
summary = "Return a parent path, leaf, or drive portion of a path."
+++
---

## Purpose

Return a parent path, leaf, or drive portion of a path.

## Basic syntax

```powershell
Split-Path [-Path] PATH [OPTIONS]
```

## Common parameters

- `-Parent`: Return the parent path.
- `-Leaf`: Return the final path component.
- `-Qualifier`: Return the drive or qualifier.
- `-Extension`: Return the extension where supported.

## Common examples

```powershell
Split-Path C:\Logs\app.log -Parent
Split-Path C:\Logs\app.log -Leaf
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Split-Path -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/split-path/) for the complete syntax.
