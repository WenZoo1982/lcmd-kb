+++
summary = "Get modules installed through PowerShellGet."
+++
---

## Purpose

Get modules installed through PowerShellGet.

## Basic syntax

```powershell
Get-InstalledModule [NAME] [OPTIONS]
```

## Common parameters

- `-Name`: Filter by module name.
- `-RequiredVersion`: Select a specific version.
- `-AllVersions`: Show all installed versions.

## Common examples

```powershell
Get-InstalledModule
Get-InstalledModule -Name Pester -AllVersions
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Get-InstalledModule -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-installedmodule/) for the complete syntax.
