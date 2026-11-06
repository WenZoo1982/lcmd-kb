+++
summary = "查看通过 PowerShellGet 安装的模块。"
+++
---

## 用途

查看通过 PowerShellGet 安装的模块。

## 基本语法

```powershell
Get-InstalledModule [名称] [选项]
```

## 常用参数

- `-Name`：按名称筛选。
- `-RequiredVersion`：指定版本。
- `-AllVersions`：显示所有已安装版本。

## 常用示例

```powershell
Get-InstalledModule
Get-InstalledModule -Name Pester -AllVersions
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Get-InstalledModule -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-installedmodule/)。
