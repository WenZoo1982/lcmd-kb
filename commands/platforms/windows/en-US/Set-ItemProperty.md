+++
summary = "Set a property on a file, registry key, or another item."
+++
---

## Purpose

Set a property on a file, registry key, or another item.

## Basic syntax

```powershell
Set-ItemProperty [-Path] PATH [-Name] PROPERTY [-Value] VALUE
```

## Common parameters

- `-Name`: Property name.
- `-Value`: New value.
- `-Type`: Specify the property type where supported.
- `-WhatIf`: Preview the operation.

## Common examples

```powershell
Set-ItemProperty -Path 'HKCU:\Environment' -Name Demo -Value '1' -WhatIf
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Set-ItemProperty -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/set-itemproperty/) for the complete syntax.
