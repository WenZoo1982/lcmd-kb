+++
summary = "Stop a running scheduled task."
+++
---

## Purpose

Stop a running scheduled task.

## Basic syntax

```powershell
Stop-ScheduledTask [-TaskName] NAME [OPTIONS]
```

## Common parameters

- `-TaskName`: Specify the task name.
- `-TaskPath`: Specify the task path.

## Common examples

```powershell
Stop-ScheduledTask -TaskName 'MyBackup'
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Stop-ScheduledTask -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/stop-scheduledtask/) for the complete syntax.
