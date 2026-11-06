+++
summary = "Read the contents of a file."
+++
---

## Purpose

Read the contents of a file.

## Basic syntax

```powershell
Get-Content [-Path] PATH [OPTIONS]
```

## Common parameters

- `-TotalCount`: Read a specified number of lines from the beginning.
- `-Tail`: Read the last specified number of lines.
- `-Wait`: Wait for and display appended content.
- `-Raw`: Read the file as one string.
- `-Encoding`: Specify text encoding.

## Common examples

```powershell
Get-Content .\app.log
Get-Content .\app.log -Tail 50
Get-Content .\app.log -Wait -Tail 20
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Get-Content -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-content/) for the complete syntax.
