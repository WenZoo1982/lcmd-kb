+++
summary = "Import a module into the current session."
+++
---

## Purpose

Import a module into the current session.

## Basic syntax

```powershell
Import-Module [-Name] MODULE [OPTIONS]
```

## Common parameters

- `-Force`: Reimport a module.
- `-Global`: Import into global session state where applicable.
- `-Prefix`: Add a prefix to imported commands.
- `-PassThru`: Return the module object.

## Common examples

```powershell
Import-Module Microsoft.PowerShell.Management
Import-Module .\MyTools.psm1 -Force
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Import-Module -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/import-module/) for the complete syntax.
