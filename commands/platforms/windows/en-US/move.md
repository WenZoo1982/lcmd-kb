+++
summary = "Move files or directories; in PowerShell, move is an alias for Move-Item."
+++
---

## Purpose

Move files or directories, optionally changing their names in the process. In Windows PowerShell 5.1, move is an alias for Move-Item.

## Basic syntax

~~~powershell
move [-Path] SOURCE [-Destination] DESTINATION [OPTIONS]
~~~

## Common parameters

| Goal | Command | Description |
|---|---|---|
| Move a file | move .\a.txt D:\Backup\ | Move a file to a destination directory |
| Move and rename | move .\a.txt .\b.txt | Change the file name while moving |
| Move a directory | move .\Project D:\Backup\ | Move an entire directory |
| Force the operation | move .\a.txt D:\Backup\ -Force | Attempt to overwrite a destination item |
| Preview the operation | move .\a.txt D:\Backup\ -WhatIf | Show the planned operation |

## Common examples

~~~powershell
move .\report.txt D:\Backup\
move .\old-name.txt .\new-name.txt
~~~

## Notes

PowerShell move invokes Move-Item and supports parameters such as -Force and -WhatIf.

CMD move uses options such as /y and /-y. Do not use CMD options directly with PowerShell.

Full PowerShell syntax: Get-Help Move-Item -Full.