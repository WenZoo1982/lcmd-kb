+++
summary = "Create a new property on a registry key or another item."
+++
---

## Purpose

Create a new property on a registry key or another item.

## Basic syntax

```powershell
New-ItemProperty [-Path] PATH [-Name] NAME [-Value] VALUE [OPTIONS]
```

## Common parameters

- `-PropertyType`: Set a registry value type such as String, DWord, or QWord.
- `-Force`: Replace an existing property where supported.
- `-WhatIf`: Preview the operation.

## Common examples

```powershell
New-ItemProperty -Path 'HKCU:\Environment' -Name DemoValue -Value 'Hello' -PropertyType String -WhatIf
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help New-ItemProperty -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/new-itemproperty/) for the complete syntax.
