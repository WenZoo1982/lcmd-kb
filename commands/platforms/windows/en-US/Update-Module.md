+++
summary = "Update modules installed through PowerShellGet."
+++
---

## Purpose

Update modules installed through PowerShellGet.

## Basic syntax

```powershell
Update-Module [-Name] MODULE [OPTIONS]
```

## Common parameters

- `-Name`: Specify a module.
- `-Force`: Force the update.
- `-WhatIf`: Preview the update.

## Common examples

```powershell
Update-Module -Name Pester
Update-Module -Name Pester -WhatIf
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Update-Module -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/update-module/) for the complete syntax.
