+++
summary = "Generate a terminating error and interrupt the current execution flow."
+++
---

## Purpose

Generate a terminating error and interrupt the current execution flow.

## Basic syntax

```powershell
throw [MESSAGE_OR_EXCEPTION]
```

## Common parameters

- `throw`: Throw an exception or error message.
- Use with `try` / `catch` to handle exceptions.

## Common examples

```powershell
if (-not (Test-Path .\config.json)) { throw 'Configuration file not found' }
try { throw 'Something failed' } catch { $_.Exception.Message }
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Throw -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/throw/) for the complete syntax.
