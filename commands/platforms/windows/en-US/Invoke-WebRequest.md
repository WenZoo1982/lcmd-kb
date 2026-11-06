+++
summary = "Send HTTP/HTTPS requests and retrieve response content."
+++
---

## Purpose

Send HTTP/HTTPS requests and retrieve response content.

## Basic syntax

```powershell
Invoke-WebRequest [-Uri] URI [OPTIONS]
```

## Common parameters

- `-Method`: Select GET, POST, PUT, and other methods.
- `-Headers`: Set request headers.
- `-Body`: Set the request body.
- `-OutFile`: Save the response to a file.
- `-TimeoutSec`: Set the timeout.
- `-UseBasicParsing`: Common in Windows PowerShell 5.1; unnecessary in PowerShell 7.

## Common examples

```powershell
Invoke-WebRequest https://example.com
Invoke-WebRequest https://example.com -OutFile .\page.html
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Invoke-WebRequest -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/invoke-webrequest/) for the complete syntax.
