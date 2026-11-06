+++
summary = "Create or replace the contents of a file."
+++
---

## Purpose

Create or replace the contents of a file.

## Basic syntax

```powershell
Set-Content [-Path] PATH [-Value] VALUE [OPTIONS]
```

## Common parameters

- `-Value`: Specify content to write.
- `-Encoding`: Specify encoding.
- `-NoNewline`: Do not append a newline.
- `-Force`: Override restricted items where supported.

## Common examples

```powershell
Set-Content .\status.txt 'Ready'
Set-Content .\data.txt -Value 'Hello' -Encoding utf8
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Set-Content -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/set-content/) for the complete syntax.
