+++
summary = "Uninstall a module installed through PowerShellGet."
+++
---

## Purpose

Uninstall a module installed through PowerShellGet.

## Basic syntax

```powershell
Uninstall-Module [-Name] MODULE [OPTIONS]
```

## Common parameters

- `-AllVersions`: Uninstall all installed versions.
- `-RequiredVersion`: Uninstall a specific version.
- `-Force`: Force uninstallation.

## Common examples

```powershell
Uninstall-Module -Name Pester -WhatIf
Uninstall-Module -Name Pester -AllVersions
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Uninstall-Module -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/uninstall-module/) for the complete syntax.
