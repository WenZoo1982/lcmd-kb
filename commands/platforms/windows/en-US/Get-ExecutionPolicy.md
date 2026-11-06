+++
summary = "Get the PowerShell script execution policy."
+++
---

## Purpose

Get the PowerShell script execution policy.

## Basic syntax

```powershell
Get-ExecutionPolicy [OPTIONS]
```

## Common parameters

- `-List`: Show policies for all scopes.
- `-Scope`: Get the policy for a specified scope.

## Common examples

```powershell
Get-ExecutionPolicy
Get-ExecutionPolicy -List
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Get-ExecutionPolicy -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-executionpolicy/) for the complete syntax.
