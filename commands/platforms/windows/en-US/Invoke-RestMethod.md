+++
summary = "Call REST APIs and automatically parse common response formats."
+++
---

## Purpose

Call REST APIs and automatically parse common response formats.

## Basic syntax

```powershell
Invoke-RestMethod [-Uri] URI [OPTIONS]
```

## Common parameters

- `-Method`: Select the HTTP method.
- `-Headers`: Set request headers.
- `-Body`: Supply the request body.
- `-ContentType`: Set the content type.
- `-Authentication`: Select an authentication method where supported.

## Common examples

```powershell
Invoke-RestMethod https://api.github.com
Invoke-RestMethod -Uri https://httpbin.org/post -Method Post -Body @{name='LCMD'}
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Invoke-RestMethod -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/invoke-restmethod/) for the complete syntax.
