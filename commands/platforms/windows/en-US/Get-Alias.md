+++
summary = "Get aliases and the commands they reference."
+++
---

## Purpose

Get aliases and the commands they reference.

## Basic syntax

```powershell
Get-Alias [[-Name] ALIAS] [OPTIONS]
```

## Common parameters

- `-Name`: Filter by alias name.
- `-Definition`: Filter by the referenced command.

## Common examples

```powershell
Get-Alias
Get-Alias ls
Get-Alias -Definition Get-ChildItem
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Get-Alias -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-alias/) for the complete syntax.
