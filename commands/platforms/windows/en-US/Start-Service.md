+++
summary = "Start one or more services."
+++
---

## Purpose

Start one or more services.

## Basic syntax

```powershell
Start-Service [-Name] NAME [OPTIONS]
```

## Common parameters

- `-Name`: Specify the service name.
- `-PassThru`: Return the service object.
- `-WhatIf`: Preview the operation.

## Common examples

```powershell
Start-Service -Name Spooler
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Start-Service -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/start-service/) for the complete syntax.
