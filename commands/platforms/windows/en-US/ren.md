+++
summary = "Rename files or directories; in PowerShell, ren is an alias for Rename-Item."
+++
---

## Purpose

Rename a file or directory. In Windows PowerShell 5.1, ren is an alias for Rename-Item.

## Basic syntax

~~~powershell
ren [-Path] OLD_NAME [-NewName] NEW_NAME [OPTIONS]
~~~

## Common parameters

| Goal | Command | Description |
|---|---|---|
| Rename a file | ren .\old.txt new.txt | Change the file name |
| Rename a directory | ren .\OldFolder NewFolder | Change the directory name |
| Use a full path | ren C:\Temp\a.txt b.txt | Rename an item in its existing directory |
| Preview the operation | ren .\old.txt new.txt -WhatIf | Preview the rename |

## Common examples

~~~powershell
ren .\report-old.txt report.txt
ren .\OldFolder NewFolder -WhatIf
~~~

## Notes

The -NewName parameter normally takes the new name, not a destination directory path. Use Move-Item when you need to move an item.

CMD ren uses the form ren OLD_NAME NEW_NAME and supports different wildcard behavior. Do not assume CMD wildcard rules apply to PowerShell.

Full PowerShell syntax: Get-Help Rename-Item -Full.