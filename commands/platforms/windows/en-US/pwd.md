+++
summary = "Display the current working location; in PowerShell, pwd is an alias for Get-Location."
+++
---

## Purpose

Display the working location of the current PowerShell session. In Windows PowerShell 5.1, pwd is an alias for Get-Location.

## Basic syntax

~~~powershell
pwd
~~~

## Common parameters

| Goal | Command | Description |
|---|---|---|
| Show the current location | pwd | Display the current working location |
| Get the path as a string | (pwd).Path | Output the current file-system path |
| Save the current path | $current = (pwd).Path | Store the path in a variable |

## Common examples

~~~powershell
pwd
$current = (pwd).Path
Write-Output $current
~~~

## Notes

PowerShell Get-Location returns a location object, not just plain text. When the current location belongs to a provider other than the file system, such as the Registry or Environment provider, the displayed location may not be a normal disk path.

CMD has no standard internal command named pwd. Use cd to display the current directory in CMD.

Full PowerShell syntax: Get-Help Get-Location -Full.