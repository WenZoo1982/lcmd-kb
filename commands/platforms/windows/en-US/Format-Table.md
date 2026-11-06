+++
summary = "Format objects as a table."
+++
---

## Purpose

Format objects as a table.

## Basic syntax

```powershell
OBJECT | Format-Table [PROPERTY] [OPTIONS]
```

## Common parameters

- `-AutoSize`: Adjust column widths to content.
- `-Wrap`: Allow cell content to wrap.
- `-Property`: Select displayed properties.

## Common examples

```powershell
Get-Process | Format-Table Name,Id,CPU -AutoSize
Get-Service | Format-Table -AutoSize
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Format-Table -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/format-table/) for the complete syntax.
