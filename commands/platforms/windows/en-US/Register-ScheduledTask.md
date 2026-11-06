+++
summary = "Register a Windows scheduled task (ScheduledTasks module)."
+++
---

## Purpose

Register a Windows scheduled task (ScheduledTasks module).

## Basic syntax

```powershell
Register-ScheduledTask [-TaskName] NAME [OPTIONS]
```

## Common parameters

- `-Action`: Specify the task action.
- `-Trigger`: Specify the trigger.
- `-User`: Specify the run-as account.
- `-RunLevel`: Set the run level.

## Common examples

```powershell
$action = New-ScheduledTaskAction -Execute 'notepad.exe'
$trigger = New-ScheduledTaskTrigger -Daily -At 9am
Register-ScheduledTask -TaskName 'OpenNotepadDaily' -Action $action -Trigger $trigger -WhatIf
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Register-ScheduledTask -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/register-scheduledtask/) for the complete syntax.
