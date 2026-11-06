+++
summary = "Remove a PowerShell drive from the current session."
+++
---

## Purpose

Remove a PowerShell drive from the current session.

## Basic syntax

```powershell
Remove-PSDrive [-Name] NAME [OPTIONS]
```

## Common parameters

- `-Name`: Specify the drive name.
- `-Force`: Remove a drive that is in use where supported.

## Common examples

```powershell
Remove-PSDrive -Name Data
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Remove-PSDrive -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/remove-psdrive/) for the complete syntax.
