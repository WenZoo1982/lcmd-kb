+++
summary = "Remove directories; in PowerShell, rmdir is an alias for Remove-Item."
+++
---

## Purpose

Remove directories or other file-system items. In Windows PowerShell 5.1, rmdir is an alias for Remove-Item.

## Basic syntax

~~~powershell
rmdir [-Path] PATH [OPTIONS]
~~~

## Common parameters

| Goal | Command | Description |
|---|---|---|
| Remove an empty directory | rmdir .\OldFolder | Remove the specified directory |
| Remove a directory and its contents | rmdir .\Temp -Recurse | Remove the directory recursively |
| Force removal | rmdir .\Temp -Recurse -Force | Attempt to force removal |
| Preview the operation | rmdir .\Temp -Recurse -WhatIf | Preview the removal |

## Common examples

~~~powershell
rmdir .\EmptyFolder
rmdir .\Temp -Recurse -WhatIf
~~~

## Notes

In PowerShell, rmdir, rd, and del all invoke Remove-Item. CMD's rmdir /s /q options cannot be used directly in PowerShell.

Full PowerShell syntax: Get-Help Remove-Item -Full.