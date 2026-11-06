+++
summary = "Remove a property from a file, registry key, or another item."
+++
---

## Purpose

Remove a property from a file, registry key, or another item.

## Basic syntax

```powershell
Remove-ItemProperty [-Path] PATH [-Name] PROPERTY [OPTIONS]
```

## Common parameters

- `-Name`: Specify the property to remove.
- `-Force`: Remove restricted properties where supported.
- `-WhatIf`: Preview the operation.

## Common examples

```powershell
Remove-ItemProperty -Path 'HKCU:\Environment' -Name DemoValue -WhatIf
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Remove-ItemProperty -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/remove-itemproperty/) for the complete syntax.
