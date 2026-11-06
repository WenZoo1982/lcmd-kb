+++
summary = "Get the Authenticode signature information for a file."
+++
---

## Purpose

Get the Authenticode signature information for a file.

## Basic syntax

```powershell
Get-AuthenticodeSignature [-FilePath] FILE
```

## Common parameters

- `-FilePath`: Specify the file to inspect.
- Check `Status` and `SignerCertificate` for signature details.

## Common examples

```powershell
Get-AuthenticodeSignature .\setup.exe
Get-ChildItem .\*.ps1 | Get-AuthenticodeSignature
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Get-AuthenticodeSignature -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-authenticodesignature/) for the complete syntax.
