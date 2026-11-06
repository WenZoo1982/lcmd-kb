+++
summary = "Combine path segments using the provider's path separator."
+++
---

## Purpose

Combine path segments using the provider's path separator.

## Basic syntax

```powershell
Join-Path [-Path] PARENT [-ChildPath] CHILD
```

## Common parameters

- `-Path`: Parent path.
- `-ChildPath`: Child path.
- `-Resolve`: Resolve and return existing paths.

## Common examples

```powershell
Join-Path C:\Logs app.log
Join-Path $HOME Documents
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Join-Path -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/join-path/) for the complete syntax.
