+++
summary = "Change the current working location; in PowerShell, chdir is an alias for Set-Location."
+++
---

## Purpose

Change the current working location. In Windows PowerShell 5.1, chdir and cd are both aliases for Set-Location.

## Basic syntax

~~~powershell
chdir [[-Path] PATH]
~~~

## Common parameters

| Goal | Command | Description |
|---|---|---|
| Change to a directory | chdir C:\Windows | Move to the specified directory |
| Go to the parent directory | chdir .. | Move up one directory |
| Go to the user home directory | chdir ~ | Move to the current user's home directory |
| Change to another drive | chdir D:\Downloads | Move to the specified path |

## Common examples

~~~powershell
chdir D:\Project
chdir ..
~~~

## Notes

In PowerShell, chdir and cd have the same behavior. CMD's cd /d option does not apply to PowerShell; specify the full path to change drives.

Full PowerShell syntax: Get-Help Set-Location -Full.