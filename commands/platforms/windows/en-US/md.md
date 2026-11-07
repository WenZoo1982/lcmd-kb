+++
summary = "Create a directory; in PowerShell, md is an alias for the mkdir function."
+++
---

## Purpose

Create a directory. In Windows PowerShell 5.1, md is an alias for the mkdir function, which uses New-Item to create a directory.

## Basic syntax

~~~powershell
md PATH
~~~

## Common parameters

| Goal | Command | Description |
|---|---|---|
| Create a directory | md .\Logs | Create Logs in the current directory |
| Create nested directories | md .\Data\Archive -Force | Create the directory path |
| Specify a full path | md D:\Backup\Logs | Create a directory at the specified location |

## Common examples

~~~powershell
md .\Logs
md D:\Backup\Daily -Force
~~~

## Notes

In PowerShell, md is an alias for mkdir, which is a function that creates a directory through New-Item. CMD md is a separate internal command; its parameter behavior is not identical.

Full PowerShell syntax: Get-Help New-Item -Full.