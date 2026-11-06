+++
summary = "Get Windows scheduled tasks."
+++
---

## Purpose

Get Windows scheduled tasks.

## Basic syntax

```powershell
Get-ScheduledTask [OPTIONS]
```

## Common parameters

- `-TaskName`: Filter by task name.
- `-TaskPath`: Filter by task path.
- `-TaskPath '\'`: Query tasks in the root folder.

## Common examples

```powershell
Get-ScheduledTask
Get-ScheduledTask -TaskName '*Update*'
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Get-ScheduledTask -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-scheduledtask/) for the complete syntax.
