+++
summary = "Start a registered scheduled task."
+++
---

## Purpose

Start a registered scheduled task.

## Basic syntax

```powershell
Start-ScheduledTask [-TaskName] NAME [OPTIONS]
```

## Common parameters

- `-TaskName`: Specify the task name.
- `-TaskPath`: Specify the task path.

## Common examples

```powershell
Start-ScheduledTask -TaskName 'MyBackup'
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Start-ScheduledTask -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/start-scheduledtask/) for the complete syntax.
