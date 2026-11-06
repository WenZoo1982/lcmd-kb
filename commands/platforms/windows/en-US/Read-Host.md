+++
summary = "Read a line of input from the console."
+++
---

## Purpose

Read a line of input from the console.

## Basic syntax

```powershell
Read-Host [-Prompt] PROMPT [OPTIONS]
```

## Common parameters

- `-Prompt`: Display an input prompt.
- `-AsSecureString`: Read sensitive input as a secure string.

## Common examples

```powershell
$name = Read-Host 'Enter a name'
$secret = Read-Host 'Enter a password' -AsSecureString
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Read-Host -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/read-host/) for the complete syntax.
