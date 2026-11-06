+++
summary = "Invoke a method on a CIM instance or class."
+++
---

## Purpose

Invoke a method on a CIM instance or class.

## Basic syntax

```powershell
Invoke-CimMethod [-InputObject] OBJECT [-MethodName] METHOD [OPTIONS]
```

## Common parameters

- `-MethodName`: Specify the method to invoke.
- `-Arguments`: Supply method arguments.
- `-ClassName`: Specify a CIM class.

## Common examples

```powershell
$os = Get-CimInstance Win32_OperatingSystem
$os | Invoke-CimMethod -MethodName Reboot
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Invoke-CimMethod -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/invoke-cimmethod/) for the complete syntax.
