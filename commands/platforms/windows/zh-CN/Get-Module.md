+++
summary = "查看已加载或可用的模块。"
+++
---

## 用途

查看已加载或可用的模块。

## 基本语法

```powershell
Get-Module [名称] [选项]
```

## 常用参数

- `-ListAvailable`：列出可用模块。
- `-Name`：按模块名筛选。
- `-All`：显示嵌套模块。

## 常用示例

```powershell
Get-Module
Get-Module -ListAvailable
Get-Module -ListAvailable Microsoft.PowerShell.*
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Get-Module -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-module/)。
