+++
summary = "Change the current working location; in PowerShell, cd is an alias for Set-Location."
+++
---

## Purpose

Change the current working location. In Windows PowerShell 5.1, cd is a common alias for Set-Location.

## Basic syntax

~~~powershell
cd [[-Path] PATH]
~~~

## Common parameters

| Goal | Command | Description |
|---|---|---|
| Show the current location | pwd | Display the current working location |
| Change to a directory | cd C:\Windows | Move to the specified directory |
| Go to the parent directory | cd .. | Move up one directory |
| Go to the user home directory | cd ~ | Move to the current user's home directory |
| Change drives | cd D:\ | Change to a path on drive D |

## Common examples

~~~powershell
cd D:\Downloads
cd ..
cd ~
~~~

## Notes

In CMD, cd /d D:\PATH changes both the drive and directory. PowerShell does not use /d; specify the full path instead.

Full PowerShell syntax: Get-Help Set-Location -Full.