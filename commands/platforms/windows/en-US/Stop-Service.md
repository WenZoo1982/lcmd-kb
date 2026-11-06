+++
summary = "Stop one or more services."
+++
---

## Purpose

Stop one or more services.

## Basic syntax

```powershell
Stop-Service [-Name] NAME [OPTIONS]
```

## Common parameters

- `-Name`: Specify the service name.
- `-Force`: Stop the service and dependent services; use carefully.
- `-NoWait`: Do not wait for the stop to complete.
- `-WhatIf`: Preview the operation.

## Common examples

```powershell
Stop-Service -Name Spooler -WhatIf
Stop-Service -Name Spooler
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Stop-Service -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/stop-service/) for the complete syntax.
