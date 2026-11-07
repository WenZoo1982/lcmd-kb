+++
summary = "Remove files or directories; in PowerShell, erase is an alias for Remove-Item."
+++
---

## Purpose

Remove files or directories. In Windows PowerShell 5.1, erase and del are both aliases for Remove-Item.

## Basic syntax

~~~powershell
erase [-Path] PATH [OPTIONS]
~~~

## Common parameters

| Goal | Command | Description |
|---|---|---|
| Remove a file | erase .\old.txt | Remove the specified file |
| Remove matching files | erase .\*.tmp | Remove files matching the pattern |
| Remove a directory recursively | erase .\Temp -Recurse | Remove a directory and its contents |
| Force removal | erase .\old.txt -Force | Attempt to remove read-only or hidden items |
| Preview the operation | erase .\Temp -Recurse -WhatIf | Preview without performing the operation |

## Common examples

~~~powershell
erase .\cache\*.tmp
erase .\old-folder -Recurse -WhatIf
~~~

## Notes

In PowerShell, erase and del have the same behavior; both invoke Remove-Item. Use -WhatIf to preview a removal before performing it.

CMD erase is a synonym for its internal del command and uses slash-style options. Do not use CMD options directly in PowerShell.

Full PowerShell syntax: Get-Help Remove-Item -Full.