+++
summary = "Get services on the local computer."
+++
---

## Purpose

Get services on the local computer.

## Basic syntax

```powershell
Get-Service [[-Name] NAME] [OPTIONS]
```

## Common parameters

- `-Name`: Filter by service name.
- `-DisplayName`: Filter by display name.
- `-DependentServices`: Include dependent services.
- `-RequiredServices`: Include required services.

## Common examples

```powershell
Get-Service
Get-Service -Name Spooler
Get-Service | Where-Object Status -eq 'Running'
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Get-Service -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-service/) for the complete syntax.
