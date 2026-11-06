+++
summary = "Query Windows event logs, including modern logs and structured filters."
+++
---

## Purpose

Query Windows event logs, including modern logs and structured filters.

## Basic syntax

```powershell
Get-WinEvent [-LogName] LOG_NAME [OPTIONS]
```

## Common parameters

- `-LogName`: Specify the event log channel.
- `-FilterHashtable`: Filter with a hashtable.
- `-FilterXPath`: Filter with XPath.
- `-MaxEvents`: Limit the number of events returned.

## Common examples

```powershell
Get-WinEvent -LogName System -MaxEvents 20
Get-WinEvent -FilterHashtable @{LogName='System'; Level=2} -MaxEvents 30
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Get-WinEvent -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-winevent/) for the complete syntax.
