+++
summary = "Remove files or directories; in PowerShell, rd is an alias for Remove-Item."
+++
---

## Purpose

Remove files or directories. In Windows PowerShell 5.1, rd is an alias for Remove-Item.

## Basic syntax

~~~powershell
rd [-Path] PATH [OPTIONS]
~~~

## Common parameters

| Goal | Command | Description |
|---|---|---|
| Remove an empty directory | rd .\OldFolder | Remove the specified directory |
| Remove a directory and its contents | rd .\Temp -Recurse | Remove the directory recursively |
| Force removal | rd .\Temp -Recurse -Force | Attempt to force removal |
| Preview the operation | rd .\Temp -Recurse -WhatIf | Preview the removal |

## Common examples

~~~powershell
rd .\EmptyFolder
rd .\Temp -Recurse -WhatIf
~~~

## Notes

Removing a directory and its contents may be irreversible. Use -WhatIf to preview the operation first.

CMD rd uses options such as /s and /q. PowerShell uses -Recurse and -Force instead; do not mix the parameter styles.

Full PowerShell syntax: Get-Help Remove-Item -Full.