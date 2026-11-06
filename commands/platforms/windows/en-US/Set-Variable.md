+++
summary = "Create or change a variable."
+++
---

## Purpose

Create or change a variable.

## Basic syntax

```powershell
Set-Variable [-Name] NAME [-Value] VALUE [OPTIONS]
```

## Common parameters

- `-Name`: Variable name.
- `-Value`: Variable value.
- `-Option`: Set variable options.
- `-Scope`: Select a scope.
- `-Force`: Override protected variables where supported.

## Common examples

```powershell
Set-Variable -Name AppMode -Value 'Test'
$AppMode
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Set-Variable -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/set-variable/) for the complete syntax.
