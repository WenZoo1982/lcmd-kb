+++
summary = "Get CIM instances from a local or remote computer."
+++
---

## Purpose

Get CIM instances from a local or remote computer.

## Basic syntax

```powershell
Get-CimInstance [-ClassName] CLASS [OPTIONS]
```

## Common parameters

- `-ClassName`: Specify the CIM class.
- `-ComputerName`: Specify a remote computer where supported.
- `-Filter`: Apply a WQL filter.
- `-Property`: Retrieve selected properties only.

## Common examples

```powershell
Get-CimInstance Win32_OperatingSystem
Get-CimInstance Win32_Process -Filter "Name='notepad.exe'"
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Get-CimInstance -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-ciminstance/) for the complete syntax.
