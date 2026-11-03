+++
summary = "List files and subdirectories, with optional filtering by name or item type."
+++
---

## Purpose

List files and subdirectories in the current or a specified directory. In PowerShell, `dir` is an alias for `Get-ChildItem`.

## Basic syntax

```powershell
dir [path] [options]
```

## Common options

| Goal | Command | Description |
|---|---|---|
| List the current directory | `dir` | Show its contents |
| List a specified directory | `dir D:\\Downloads` | Show the target directory |
| Show files only | `dir -File` | Exclude directories |
| Show directories only | `dir -Directory` | List subdirectories only |

## Common examples

```powershell
dir -File -Filter *.zip
```

List only ZIP files in the current directory.

## Notes

These options follow Windows PowerShell 5.1 `Get-ChildItem` behavior. Do not assume that CMD internal commands use the same options.
