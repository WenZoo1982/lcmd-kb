+++
summary = "List files and directories; in PowerShell, dir is an alias for Get-ChildItem."
+++
---

## Purpose

List files and subdirectories in the current or a specified directory. In Windows PowerShell 5.1, dir is a common alias for Get-ChildItem.

## Basic syntax

~~~powershell
dir [[-Path] PATH] [OPTIONS]
~~~

## Common parameters

| Goal | Command | Description |
|---|---|---|
| List the current directory | dir | Display the contents of the current directory |
| List a specified directory | dir D:\Downloads | List the specified directory |
| Show files only | dir -File | Exclude directories |
| Show directories only | dir -Directory | List subdirectories only |
| Include hidden items | dir -Force | Include hidden and system items |
| List recursively | dir -Recurse | Include the contents of subdirectories |
| Filter by name | dir -Filter *.zip | List items matching the filter |

## Common examples

~~~powershell
dir -File -Filter *.zip
dir D:\Downloads -Directory
dir . -Recurse -Filter *.log
~~~

List only ZIP files in the current directory.

## Notes

In PowerShell, dir follows the parameter rules of Get-ChildItem, including -File, -Directory, and -Recurse.

CMD dir is a different internal command. Common CMD options include /a, /s, /b, and /o. Do not use CMD's slash options directly in PowerShell. To view CMD help, run cmd /c dir /?.

Full PowerShell syntax: Get-Help Get-ChildItem -Full.