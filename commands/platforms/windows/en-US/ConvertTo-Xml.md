+++
summary = "Convert objects to an XML representation."
+++
---

## Purpose

Convert objects to an XML representation.

## Basic syntax

```powershell
OBJECT | ConvertTo-Xml [OPTIONS]
```

## Common parameters

- `-As`: Select String, Stream, or Document.
- `-Depth`: Set conversion depth.
- `-NoTypeInformation`: Omit type information.

## Common examples

```powershell
Get-Process | Select-Object -First 2 Name,Id | ConvertTo-Xml -As String
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help ConvertTo-Xml -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/convertto-xml/) for the complete syntax.
