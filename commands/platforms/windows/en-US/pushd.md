+++
summary = "Save the current location and change directories; PowerShell uses Push-Location."
+++
---

## Purpose

Save the current working location, then change to another directory. In Windows PowerShell 5.1, pushd is an alias for Push-Location.

## Basic syntax

~~~powershell
pushd PATH
~~~

## Common parameters

| Goal | Command | Description |
|---|---|---|
| Save and change location | pushd D:\Project | Save the current location and enter the target directory |
| Move to the parent directory | pushd .. | Save the current location before moving up one directory |
| Show the current location | pwd | Display the current working location |

## Common examples

~~~powershell
pushd D:\Project
# Restore the previous location when finished
popd
~~~

## Notes

pushd pushes the current location onto the location stack. Use popd to restore it later. CMD pushd may assign a temporary drive letter when given a UNC network path; PowerShell behaves differently.

Full PowerShell syntax: Get-Help Push-Location -Full.