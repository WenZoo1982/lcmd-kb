+++
summary = "Resolve DNS names and query DNS records."
+++
---

## Purpose

Resolve DNS names and query DNS records.

## Basic syntax

```powershell
Resolve-DnsName [-Name] NAME [OPTIONS]
```

## Common parameters

- `-Type`: Specify a record type such as A, AAAA, MX, or TXT.
- `-Server`: Specify a DNS server.
- `-DnsOnly`: Use DNS only.
- `-NoHostsFile`: Do not consult the Hosts file.

## Common examples

```powershell
Resolve-DnsName example.com
Resolve-DnsName example.com -Type MX
Resolve-DnsName example.com -Server 1.1.1.1
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Resolve-DnsName -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/resolve-dnsname/) for the complete syntax.
