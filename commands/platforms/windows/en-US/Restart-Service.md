+++
summary = "Stop and then start a service."
+++
---

## Purpose

Stop and then start a service.

## Basic syntax

```powershell
Restart-Service [-Name] NAME [OPTIONS]
```

## Common parameters

- `-Name`: Specify the service name.
- `-Force`: Force restart of the service and dependencies; use carefully.
- `-PassThru`: Return the service object.

## Common examples

```powershell
Restart-Service -Name Spooler
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Restart-Service -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/restart-service/) for the complete syntax.
