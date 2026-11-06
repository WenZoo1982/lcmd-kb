+++
summary = "Get the processes running on the local computer."
+++
---

## Purpose

Get the processes running on the local computer.

## Basic syntax

```powershell
Get-Process [[-Name] NAME] [OPTIONS]
```

## Common parameters

- `-Name`: Filter by process name.
- `-Id`: Filter by process ID.
- `-IncludeUserName`: Include the process owner; may require elevation.
- `-FileVersionInfo`: Get executable version information.

## Common examples

```powershell
Get-Process
Get-Process -Name chrome
Get-Process -Id 1234
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Get-Process -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-process/) for the complete syntax.
