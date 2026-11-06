+++
summary = "Search text in files or strings using literal text or regular expressions."
+++
---

## Purpose

Search text in files or strings using literal text or regular expressions.

## Basic syntax

```powershell
Select-String [-Pattern] PATTERN [-Path] PATH [OPTIONS]
```

## Common parameters

- `-Pattern`: Specify text or a regular expression.
- `-SimpleMatch`: Use literal string matching.
- `-CaseSensitive`: Match case-sensitively.
- `-Context`: Include surrounding lines.
- `-AllMatches`: Return all matches on each line.

## Common examples

```powershell
Select-String -Path .\*.log -Pattern 'error'
Get-Content .\app.log | Select-String 'timeout' -Context 2,2
```

## More parameters

This page selects practical, frequently used parameters only. Parameters and behavior may vary by PowerShell version, operating system, and module version. Run `Get-Help Select-String -Full` or consult [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/select-string/) for the complete syntax.
