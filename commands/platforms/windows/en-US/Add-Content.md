+++
summary = "Append content to a file or another item."
+++
---

## Purpose

Append content to a file or another item.

## Basic syntax

```powershell
Add-Content [-Path] PATH [-Value] VALUE [OPTIONS]
```

## Common parameters

- `-Value`: Content to append.
- `-Encoding`: Specify encoding.
- `-NoNewline`: Do not append a trailing newline.

## Common examples

```powershell
Add-Content .\app.log 'Started'
Get-Content .\app.log -Tail 5
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Add-Content -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/add-content/) for the complete syntax.
