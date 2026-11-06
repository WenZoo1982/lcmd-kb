+++
summary = "Remove variables from the current session."
+++
---

## Purpose

Remove variables from the current session.

## Basic syntax

```powershell
Remove-Variable [-Name] NAME [OPTIONS]
```

## Common parameters

- `-Name`: Specify variables to remove.
- `-Force`: Remove protected variables where supported.
- `-WhatIf`: Preview the operation.

## Common examples

```powershell
Remove-Variable -Name AppMode
Remove-Variable -Name Temp* -WhatIf
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Remove-Variable -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/remove-variable/) for the complete syntax.
