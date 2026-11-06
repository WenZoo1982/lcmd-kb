+++
summary = "Create or change a command alias."
+++
---

## Purpose

Create or change a command alias.

## Basic syntax

```powershell
Set-Alias [-Name] ALIAS [-Value] COMMAND [OPTIONS]
```

## Common parameters

- `-Name`: Alias name.
- `-Value`: Target command.
- `-Scope`: Select a scope.
- `-Option`: Set alias options.

## Common examples

```powershell
Set-Alias -Name ll -Value Get-ChildItem
ll
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Set-Alias -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/set-alias/) for the complete syntax.
