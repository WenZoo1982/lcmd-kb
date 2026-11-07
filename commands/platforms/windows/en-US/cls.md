+++
summary = "Clear the current terminal display; PowerShell uses Clear-Host."
+++
---

## Purpose

Clear the display of the current PowerShell host. In Windows PowerShell 5.1, cls is an alias for Clear-Host.

## Basic syntax

~~~powershell
cls
~~~

## Common parameters

cls does not require common parameters.

## Common examples

~~~powershell
cls
~~~

The command clears the content currently displayed in the terminal, making new output easier to read.

## Notes

cls clears only the terminal display. It does not delete command history, files, or application data. CMD also provides cls as an internal command, but the display behavior depends on the terminal host.

PowerShell command: Clear-Host.