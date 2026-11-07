+++
summary = "Copy files or directories; in PowerShell, copy is an alias for Copy-Item."
+++
---

## Purpose

Copy files or directories. In Windows PowerShell 5.1, copy is an alias for Copy-Item.

## Basic syntax

~~~powershell
copy [-Path] SOURCE [-Destination] DESTINATION [OPTIONS]
~~~

## Common parameters

| Goal | Command | Description |
|---|---|---|
| Copy a file | copy .\a.txt .\Backup\ | Copy a file to a destination directory |
| Copy and rename | copy .\a.txt .\Backup\b.txt | Specify a new file name for the copy |
| Copy a directory | copy .\Project .\Backup -Recurse | Copy directory contents recursively |
| Force the operation | copy .\a.txt .\Backup -Force | Attempt to overwrite a destination item |
| Return the copied item | copy .\a.txt .\Backup -PassThru | Output the copied object |

## Common examples

~~~powershell
copy .\report.txt D:\Backup\
copy .\Project D:\Backup\Project -Recurse
~~~

Use -Recurse when copying a directory and its contents.

## Notes

PowerShell copy invokes Copy-Item and supports parameters such as -Recurse and -Force.

CMD copy is an internal command with options such as /y, /v, and /b. The two commands have different parameter sets; do not use CMD's /y option with PowerShell. PowerShell's -Force is not identical to every CMD overwrite option.

Full PowerShell syntax: Get-Help Copy-Item -Full.