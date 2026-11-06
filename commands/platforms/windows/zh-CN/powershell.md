+++
summary = "PowerShell 常用命令速查，覆盖文件、进程、服务、网络、模块、对象管道、脚本和 Windows 管理。"
+++
---

# PowerShell 命令速查

本目录整理 PowerShell 常用内置 cmdlet 与部分 Windows 管理模块命令，强调快速查找和常见用法。

## 命令分类

- **命令发现与帮助**：`Get-Command`、`Get-Help`、`Get-Member`、`Get-Alias`
- **路径与文件**：`Get-ChildItem`、`Get-Item`、`New-Item`、`Copy-Item`、`Move-Item`、`Remove-Item`、`Rename-Item`、`Test-Path`、`Join-Path`、`Split-Path`
- **文件内容**：`Get-Content`、`Set-Content`、`Add-Content`、`Clear-Content`、`Select-String`
- **进程与服务**：`Get-Process`、`Start-Process`、`Stop-Process`、`Get-Service`、`Start-Service`、`Stop-Service`、`Restart-Service`
- **系统与事件**：`Get-ComputerInfo`、`Get-CimInstance`、`Invoke-CimMethod`、`Get-EventLog`、`Get-WinEvent`
- **网络**：`Test-Connection`、`Resolve-DnsName`、`Get-NetIPConfiguration`、`Get-NetIPAddress`、`Get-NetAdapter`、`Get-NetTCPConnection`
- **模块与执行策略**：`Get-ExecutionPolicy`、`Set-ExecutionPolicy`、`Get-Module`、`Import-Module`、`Install-Module`、`Update-Module`、`Uninstall-Module`
- **对象与管道**：`Where-Object`、`ForEach-Object`、`Sort-Object`、`Select-Object`、`Group-Object`、`Measure-Object`
- **数据格式**：`ConvertTo-Json`、`ConvertFrom-Json`、`Export-Csv`、`Import-Csv`、`Export-Clixml`、`Import-Clixml`
- **脚本与交互**：`Start-Sleep`、`Read-Host`、`Write-Output`、`Write-Host`、`Write-Error`、`Throw`、历史记录命令
- **Windows 管理**：计划任务、注册表属性、剪贴板、文件签名等命令

## 使用说明

PowerShell 命令通常采用 `动词-名词` 命名形式。命令、参数名通常不区分大小写。管道传递的是 .NET 对象，而不只是文本。

Windows PowerShell 5.1 与 PowerShell 7+ 在可用模块、参数和默认行为上存在差异。部分网络、计划任务、注册表和剪贴板命令仅适用于 Windows；部分参数仅在较新版本中提供。

## 别名提示

常见别名包括 `ls`、`dir`（`Get-ChildItem`）、`cd`（`Set-Location`）、`pwd`（`Get-Location`）、`cat`（`Get-Content`）、`cp`（`Copy-Item`）、`mv`（`Move-Item`）、`rm`（`Remove-Item`）、`ps`（`Get-Process`）。别名可能与其他 shell 不同，编写脚本时建议使用完整 cmdlet 名称。

## 更多信息

此目录是高频命令速查集，不是 PowerShell 全部命令、模块或别名的穷举列表。可使用 `Get-Command -ListImported`、`Get-Command -All` 和 `Get-Module -ListAvailable` 查看当前系统实际可用的命令与模块。
