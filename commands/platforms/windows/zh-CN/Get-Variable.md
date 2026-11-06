+++
summary = "获取当前会话中的变量。"
+++
---

## 用途

获取当前会话中的变量。

## 基本语法

```powershell
Get-Variable [[-Name] 名称] [选项]
```

## 常用参数

- `-Name`：按变量名筛选。
- `-Scope`：指定作用域。
- `-ValueOnly`：只输出变量值。

## 常用示例

```powershell
Get-Variable
Get-Variable PATH
Get-Variable -Name P*
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Get-Variable -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-variable/)。
