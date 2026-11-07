+++
summary = "Read text-file contents; in PowerShell, type is an alias for Get-Content."
+++
---

## Purpose

Read and display the contents of a text file. In Windows PowerShell 5.1, type is an alias for Get-Content.

## Basic syntax

~~~powershell
type [-Path] FILE_PATH [OPTIONS]
~~~

## Common parameters

| Goal | Command | Description |
|---|---|---|
| Display a file | type .\app.log | Output the file contents |
| Read the beginning | type .\app.log -TotalCount 20 | Read only the first 20 lines |
| Read the end | type .\app.log -Tail 50 | Read the last 50 lines |
| Follow new content | type .\app.log -Wait -Tail 20 | Wait and display appended content |
| Read as one string | type .\app.log -Raw | Return the contents as a single string |

## Common examples

~~~powershell
type .\README.txt
type .\app.log -Tail 30
~~~

## Notes

PowerShell type invokes Get-Content. Its output can be passed to other commands through the pipeline.

CMD type primarily displays text files and does not support PowerShell parameters such as -Tail, -Wait, or -Raw.

Full PowerShell syntax: Get-Help Get-Content -Full.