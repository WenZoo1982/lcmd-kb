+++
summary = "创建新变量。"
+++
---

## 用途

创建新变量。

## 基本语法

```powershell
New-Variable [-Name] 名称 [-Value] 值 [选项]
```

## 常用参数

- `-Name`：变量名称。
- `-Value`：初始值。
- `-Option Constant`：创建常量变量。
- `-Scope`：指定作用域。

## 常用示例

```powershell
New-Variable -Name BuildNumber -Value 12
New-Variable -Name Product -Value 'LCMD' -Option Constant
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help New-Variable -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/new-variable/)。
