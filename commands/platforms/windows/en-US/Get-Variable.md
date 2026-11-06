+++
summary = "Get variables in the current session."
+++
---

## Purpose

Get variables in the current session.

## Basic syntax

```powershell
Get-Variable [[-Name] NAME] [OPTIONS]
```

## Common parameters

- `-Name`: Filter by variable name.
- `-Scope`: Select a scope.
- `-ValueOnly`: Return values only.

## Common examples

```powershell
Get-Variable
Get-Variable PATH
Get-Variable -Name P*
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Get-Variable -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-variable/) for the complete syntax.
