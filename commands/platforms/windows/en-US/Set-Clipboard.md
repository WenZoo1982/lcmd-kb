+++
summary = "Set the clipboard content."
+++
---

## Purpose

Set the clipboard content.

## Basic syntax

```powershell
OBJECT | Set-Clipboard [OPTIONS]
```

## Common parameters

- `-Value`: Set clipboard content.
- `-Append`: Append text where supported.

## Common examples

```powershell
Set-Clipboard -Value 'Copied from PowerShell'
Get-Content .\note.txt | Set-Clipboard
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Set-Clipboard -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/set-clipboard/) for the complete syntax.
