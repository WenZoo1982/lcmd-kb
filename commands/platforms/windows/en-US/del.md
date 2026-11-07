+++
summary = "Remove files or directories; in PowerShell, del is an alias for Remove-Item."
+++
---

## Purpose

Remove files or directories. In Windows PowerShell 5.1, del is an alias for Remove-Item.

## Basic syntax

~~~powershell
del [-Path] PATH [OPTIONS]
~~~

## Common parameters

| Goal | Command | Description |
|---|---|---|
| Remove a file | del .\old.txt | Remove the specified file |
| Remove multiple files | del .\*.tmp | Remove files matching the pattern |
| Remove a directory and its contents | del .\Temp -Recurse | Remove a directory recursively |
| Force removal | del .\old.txt -Force | Attempt to remove read-only or hidden items |
| Preview removal | del .\Temp -Recurse -WhatIf | Show the planned operation without performing it |

## Common examples

~~~powershell
del .\*.log
del .\Temp -Recurse -WhatIf
~~~

## Notes

Removal may be difficult or impossible to undo. Use -WhatIf to preview an operation before running it.

CMD del uses options such as /p, /f, /s, and /q. PowerShell uses parameters such as -Force, -Recurse, and -Confirm. Do not mix the two parameter styles.

Full PowerShell syntax: Get-Help Remove-Item -Full.