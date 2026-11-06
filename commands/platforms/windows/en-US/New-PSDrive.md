+++
summary = "Create a temporary or persistent PowerShell drive."
+++
---

## Purpose

Create a temporary or persistent PowerShell drive.

## Basic syntax

```powershell
New-PSDrive [-Name] NAME [-PSProvider] PROVIDER [-Root] ROOT [OPTIONS]
```

## Common parameters

- `-Persist`: Create a persistent mapped network drive on Windows where supported.
- `-Credential`: Specify credentials.
- `-Scope`: Select a scope.

## Common examples

```powershell
New-PSDrive -Name Data -PSProvider FileSystem -Root C:\Data
New-PSDrive -Name Z -PSProvider FileSystem -Root \\server\share -Persist
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help New-PSDrive -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/new-psdrive/) for the complete syntax.
