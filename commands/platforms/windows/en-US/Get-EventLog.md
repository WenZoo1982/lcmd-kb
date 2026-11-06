+++
summary = "Get entries from classic Windows event logs."
+++
---

## Purpose

Get entries from classic Windows event logs.

## Basic syntax

```powershell
Get-EventLog [-LogName] LOG_NAME [OPTIONS]
```

## Common parameters

- `-Newest`: Return only the newest specified number of entries.
- `-EntryType`: Filter by entry type.
- `-Source`: Filter by source.
- `-After` / `-Before`: Filter by date.

## Common examples

```powershell
Get-EventLog -LogName System -Newest 20
Get-EventLog -LogName Application -EntryType Error -Newest 50
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Get-EventLog -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-eventlog/) for the complete syntax.
