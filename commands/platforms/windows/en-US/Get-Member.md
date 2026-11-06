+++
summary = "Inspect an object's properties, methods, and events."
+++
---

## Purpose

Inspect an object's properties, methods, and events.

## Basic syntax

```powershell
OBJECT | Get-Member [OPTIONS]
```

## Common parameters

- `-MemberType`: Filter by member type.
- `-Name`: Filter by member name.
- `-View`: Select a member view.

## Common examples

```powershell
Get-Process | Get-Member
Get-Service | Get-Member -MemberType Property
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Get-Member -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-member/) for the complete syntax.
