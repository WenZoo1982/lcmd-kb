+++
summary = "更新通过 PowerShellGet 安装的模块。"
+++
---

## 用途

更新通过 PowerShellGet 安装的模块。

## 基本语法

```powershell
Update-Module [-Name] 模块 [选项]
```

## 常用参数

- `-Name`：指定模块。
- `-Force`：强制更新。
- `-WhatIf`：预览更新操作。

## 常用示例

```powershell
Update-Module -Name Pester
Update-Module -Name Pester -WhatIf
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Update-Module -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/update-module/)。
