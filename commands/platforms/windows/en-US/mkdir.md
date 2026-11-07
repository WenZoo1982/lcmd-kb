+++
summary = "Create a directory; in PowerShell, mkdir is a function that creates a Directory item."
+++
---

## Purpose

Create a directory. In Windows PowerShell 5.1, mkdir is a function that creates a directory through New-Item.

## Basic syntax

~~~powershell
mkdir PATH
~~~

## Common parameters

| Goal | Command | Description |
|---|---|---|
| Create a directory | mkdir .\Logs | Create a Logs directory |
| Create nested directories | mkdir .\Data\Archive -Force | Create the directory path |
| Specify a full path | mkdir D:\Backup\Logs | Create a directory at the specified location |

## Common examples

~~~powershell
mkdir .\Logs
mkdir D:\Backup\Daily -Force
~~~

## Notes

In PowerShell, mkdir is a function rather than an alias for New-Item; md is an alias for mkdir. CMD mkdir is a separate internal command with different parameter rules.

Full PowerShell syntax: Get-Help New-Item -Full.