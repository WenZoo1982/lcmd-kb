+++
summary = "Quick reference for commonly used PowerShell commands covering files, processes, services, networking, modules, pipelines, scripting, and Windows administration."
+++
---

# PowerShell command quick reference

This directory collects commonly used built-in PowerShell cmdlets and selected Windows administration module commands, focusing on quick lookup and practical usage.

## Command groups

- **Discovery and help**: `Get-Command`, `Get-Help`, `Get-Member`, `Get-Alias`
- **Paths and files**: `Get-ChildItem`, `Get-Item`, `New-Item`, `Copy-Item`, `Move-Item`, `Remove-Item`, `Rename-Item`, `Test-Path`, `Join-Path`, `Split-Path`
- **File content**: `Get-Content`, `Set-Content`, `Add-Content`, `Clear-Content`, `Select-String`
- **Processes and services**: `Get-Process`, `Start-Process`, `Stop-Process`, `Get-Service`, `Start-Service`, `Stop-Service`, `Restart-Service`
- **System and events**: `Get-ComputerInfo`, `Get-CimInstance`, `Invoke-CimMethod`, `Get-EventLog`, `Get-WinEvent`
- **Networking**: `Test-Connection`, `Resolve-DnsName`, `Get-NetIPConfiguration`, `Get-NetIPAddress`, `Get-NetAdapter`, `Get-NetTCPConnection`
- **Modules and execution policy**: `Get-ExecutionPolicy`, `Set-ExecutionPolicy`, `Get-Module`, `Import-Module`, `Install-Module`, `Update-Module`, `Uninstall-Module`
- **Objects and pipelines**: `Where-Object`, `ForEach-Object`, `Sort-Object`, `Select-Object`, `Group-Object`, `Measure-Object`
- **Data formats**: `ConvertTo-Json`, `ConvertFrom-Json`, `Export-Csv`, `Import-Csv`, `Export-Clixml`, `Import-Clixml`
- **Scripting and interaction**: `Start-Sleep`, `Read-Host`, `Write-Output`, `Write-Host`, `Write-Error`, `Throw`, and history commands
- **Windows administration**: scheduled tasks, registry properties, clipboard, and file signatures

## Usage notes

PowerShell commands commonly use the `Verb-Noun` naming convention. Command and parameter names are generally case-insensitive. The pipeline passes .NET objects, not merely text.

Windows PowerShell 5.1 and PowerShell 7+ differ in available modules, parameters, and default behavior. Some networking, scheduled-task, registry, and clipboard commands are Windows-specific; some parameters are available only in newer versions.

## Alias notes

Common aliases include `ls` and `dir` (`Get-ChildItem`), `cd` (`Set-Location`), `pwd` (`Get-Location`), `cat` (`Get-Content`), `cp` (`Copy-Item`), `mv` (`Move-Item`), `rm` (`Remove-Item`), and `ps` (`Get-Process`). Aliases can differ from those in other shells. Use full cmdlet names in scripts.

## More information

This is a curated high-frequency reference, not an exhaustive catalog of every PowerShell command, module, or alias. Use `Get-Command -ListImported`, `Get-Command -All`, and `Get-Module -ListAvailable` to inspect commands and modules available on your system.
