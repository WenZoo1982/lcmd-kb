+++
summary = "Write text or objects to the pipeline; in PowerShell, echo is an alias for Write-Output."
+++
---

## Purpose

Write text or objects to the pipeline. In Windows PowerShell 5.1, echo is an alias for Write-Output.

## Basic syntax

~~~powershell
echo TEXT
~~~

## Common parameters

echo is an alias for Write-Output. It is commonly used to write text directly or pass output to another command through the pipeline.

## Common examples

~~~powershell
echo "Hello World"
echo "LCMD" | Set-Content .\name.txt
echo "alpha", "beta" | ForEach-Object { $_ }
~~~

Write text or pass the output to a command later in the pipeline.

## Notes

PowerShell echo writes objects to the pipeline. It is not equivalent to CMD's echo on or echo off, which control command-echo behavior. In PowerShell, echo off simply writes the text "off".

Full PowerShell syntax: Get-Help Write-Output -Full.