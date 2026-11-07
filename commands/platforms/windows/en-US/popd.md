+++
summary = "Restore a working location saved on the location stack; PowerShell uses Pop-Location."
+++
---

## Purpose

Restore a working location previously saved by pushd. In Windows PowerShell 5.1, popd is an alias for Pop-Location.

## Basic syntax

~~~powershell
popd
~~~

## Common parameters

popd usually requires no parameters. It restores the location at the top of the location stack.

## Common examples

~~~powershell
pushd D:\Project
# Perform work in the target directory
popd
~~~

After popd runs, the current location returns to the location that was active before pushd.

## Notes

A location must first be saved with pushd or Push-Location. CMD and PowerShell both provide location-stack commands, but their handling of UNC paths may differ.

Full PowerShell syntax: Get-Help Pop-Location -Full.