+++
summary = "Filter pipeline objects by condition; in PowerShell, where is an alias for Where-Object."
+++
---

## Purpose

Filter objects in the pipeline by a condition. In Windows PowerShell 5.1, where is an alias for Where-Object.

## Basic syntax

~~~powershell
COMMAND | where { CONDITION }
~~~

## Common parameters

| Goal | Command | Description |
|---|---|---|
| Filter processes | Get-Process \| where { $_.CPU -gt 10 } | Keep processes with CPU time greater than 10 |
| Filter services | Get-Service \| where { $_.Status -eq 'Running' } | Keep services that are running |
| Filter by a property | Get-ChildItem \| where { $_.Length -gt 1MB } | Keep files larger than 1 MB |

## Common examples

~~~powershell
Get-Service | where { $_.Status -eq 'Running' }
Get-ChildItem -File | where { $_.Length -gt 1MB }
~~~

## Notes

This name is easy to confuse: typing where in PowerShell normally invokes the Where-Object alias. The Windows executable locator is a separate external command named where.exe.

To locate an executable from PowerShell, explicitly run where.exe notepad.exe. Do not treat CMD's where FILE_NAME syntax as the PowerShell where alias.

Full PowerShell syntax: Get-Help Where-Object -Full.