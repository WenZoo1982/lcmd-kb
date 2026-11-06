+++
summary = "Get properties of an item; commonly used with the registry provider."
+++
---

## Purpose

Get properties of an item; commonly used with the registry provider.

## Basic syntax

```powershell
Get-ItemProperty [-Path] PATH [OPTIONS]
```

## Common parameters

- `-Name`: Retrieve selected properties only.
- `-LiteralPath`: Treat the path literally.

## Common examples

```powershell
Get-ItemProperty 'HKLM:\SOFTWARE\Microsoft\Windows NT\CurrentVersion'
Get-ItemProperty 'HKCU:\Environment'
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Get-ItemProperty -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-itemproperty/) for the complete syntax.
