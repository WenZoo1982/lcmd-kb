+++
summary = "删除当前会话中的变量。"
+++
---

## 用途

删除当前会话中的变量。

## 基本语法

```powershell
Remove-Variable [-Name] 名称 [选项]
```

## 常用参数

- `-Name`：指定变量。
- `-Force`：删除受保护变量（适用时）。
- `-WhatIf`：预览操作。

## 常用示例

```powershell
Remove-Variable -Name AppMode
Remove-Variable -Name Temp* -WhatIf
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Remove-Variable -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/remove-variable/)。
