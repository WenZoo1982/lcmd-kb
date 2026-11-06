+++
summary = "Get current TCP connections and endpoint information."
+++
---

## Purpose

Get current TCP connections and endpoint information.

## Basic syntax

```powershell
Get-NetTCPConnection [OPTIONS]
```

## Common parameters

- `-State`: Filter by connection state.
- `-LocalPort`: Filter by local port.
- `-RemoteAddress`: Filter by remote address.
- `-OwningProcess`: Filter by process ID.

## Common examples

```powershell
Get-NetTCPConnection
Get-NetTCPConnection -State Listen
Get-NetTCPConnection -LocalPort 443
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Get-NetTCPConnection -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-nettcpconnection/) for the complete syntax.
