+++
summary = "Install a module from a registered PowerShell repository."
+++
---

## Purpose

Install a module from a registered PowerShell repository.

## Basic syntax

```powershell
Install-Module [-Name] MODULE [OPTIONS]
```

## Common parameters

- `-Scope CurrentUser`: Install for the current user only.
- `-Repository`: Select a repository.
- `-RequiredVersion`: Install a specific version.
- `-Force`: Bypass some prompts and force installation.

## Common examples

```powershell
Install-Module Pester -Scope CurrentUser
Install-Module PSReadLine -Scope CurrentUser
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Install-Module -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/install-module/) for the complete syntax.
