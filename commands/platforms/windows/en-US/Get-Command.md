+++
summary = "Find available commands and inspect their type and source."
+++
---

## Purpose

Find available commands and inspect their type and source.

## Basic syntax

```powershell
Get-Command [[-Name] NAME] [OPTIONS]
```

## Common parameters

- `-Name`: Search by name or wildcard.
- `-Module`: Restrict results to a module.
- `-CommandType`: Filter by command type.
- `-All`: Show all commands with the name.

## Common examples

```powershell
Get-Command Get-Process
Get-Command *service*
Get-Command -Module Microsoft.PowerShell.Management
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Get-Command -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-command/) for the complete syntax.
