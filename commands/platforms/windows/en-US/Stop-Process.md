+++
summary = "Stop one or more processes."
+++
---

## Purpose

Stop one or more processes.

## Basic syntax

```powershell
Stop-Process [-Name] NAME [OPTIONS]
```

## Common parameters

- `-Id`: Target a process by ID.
- `-Force`: Force process termination.
- `-PassThru`: Return the process object.
- `-WhatIf`: Preview the operation.

## Common examples

```powershell
Stop-Process -Name notepad
Stop-Process -Id 1234 -WhatIf
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Stop-Process -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/stop-process/) for the complete syntax.
