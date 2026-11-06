+++
summary = "Start a process or application."
+++
---

## Purpose

Start a process or application.

## Basic syntax

```powershell
Start-Process [-FilePath] PROGRAM [OPTIONS]
```

## Common parameters

- `-ArgumentList`: Pass command-line arguments.
- `-WorkingDirectory`: Set the working directory.
- `-Verb RunAs`: Request elevation.
- `-Wait`: Wait for the process to exit.
- `-PassThru`: Return a process object.

## Common examples

```powershell
Start-Process notepad.exe
Start-Process powershell.exe -Verb RunAs
Start-Process .\setup.exe -ArgumentList '/quiet' -Wait
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Start-Process -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/start-process/) for the complete syntax.
