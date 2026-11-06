+++
summary = "Create a new variable."
+++
---

## Purpose

Create a new variable.

## Basic syntax

```powershell
New-Variable [-Name] NAME [-Value] VALUE [OPTIONS]
```

## Common parameters

- `-Name`: Variable name.
- `-Value`: Initial value.
- `-Option Constant`: Create a constant variable.
- `-Scope`: Select a scope.

## Common examples

```powershell
New-Variable -Name BuildNumber -Value 12
New-Variable -Name Product -Value 'LCMD' -Option Constant
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help New-Variable -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/new-variable/) for the complete syntax.
