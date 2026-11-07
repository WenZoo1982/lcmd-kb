+++
summary = "Sort objects in the pipeline; in PowerShell, sort is an alias for Sort-Object."
+++
---

## Purpose

Sort objects in the pipeline. In Windows PowerShell 5.1, sort is an alias for Sort-Object.

## Basic syntax

~~~powershell
COMMAND | sort [[-Property] PROPERTY] [OPTIONS]
~~~

## Common parameters

| Goal | Command | Description |
|---|---|---|
| Sort by name | Get-ChildItem \| sort Name | Sort items by name in ascending order |
| Sort by size | Get-ChildItem -File \| sort Length | Sort files by size |
| Sort descending | Get-Process \| sort CPU -Descending | Sort by CPU time in descending order |
| Remove duplicates | 'b','a','b' \| sort -Unique | Sort and remove duplicate values |

## Common examples

~~~powershell
Get-ChildItem -File | sort Length -Descending
Get-Service | sort Status, Name
~~~

## Notes

PowerShell sort invokes Sort-Object and sorts pipeline objects by their properties. Windows also provides an external text-line sorting program named sort.exe.

To sort text using the CMD-style external utility, explicitly run sort.exe. Its parameters and input/output behavior differ from Sort-Object.

Full PowerShell syntax: Get-Help Sort-Object -Full.