+++
summary = "卸载通过 PowerShellGet 安装的模块。"
+++
---

## 用途

卸载通过 PowerShellGet 安装的模块。

## 基本语法

```powershell
Uninstall-Module [-Name] 模块 [选项]
```

## 常用参数

- `-AllVersions`：卸载所有已安装版本。
- `-RequiredVersion`：卸载指定版本。
- `-Force`：强制卸载。

## 常用示例

```powershell
Uninstall-Module -Name Pester -WhatIf
Uninstall-Module -Name Pester -AllVersions
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Uninstall-Module -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/uninstall-module/)。
