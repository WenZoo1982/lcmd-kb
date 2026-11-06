+++
summary = "Set the PowerShell script execution policy."
+++
---

## Purpose

Set the PowerShell script execution policy.

## Basic syntax

```powershell
Set-ExecutionPolicy [-ExecutionPolicy] POLICY [OPTIONS]
```

## Common parameters

- `-Scope`: Select a scope such as CurrentUser or LocalMachine.
- `-Force`: Suppress confirmation prompts.
- `-WhatIf`: Preview the operation.

## Common examples

```powershell
Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned
Get-ExecutionPolicy -List
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Set-ExecutionPolicy -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/set-executionpolicy/) for the complete syntax.
