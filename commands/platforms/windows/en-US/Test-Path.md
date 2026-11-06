+++
summary = "Test whether a path or provider item exists."
+++
---

## Purpose

Test whether a path or provider item exists.

## Basic syntax

```powershell
Test-Path [-Path] PATH [OPTIONS]
```

## Common parameters

- `-PathType`: Check for Leaf, Container, or Any.
- `-IsValid`: Check path syntax only.
- `-LiteralPath`: Treat the path literally.

## Common examples

```powershell
Test-Path .\config.json
Test-Path C:\Windows -PathType Container
Test-Path 'HKLM:\Software'
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Test-Path -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/test-path/) for the complete syntax.
