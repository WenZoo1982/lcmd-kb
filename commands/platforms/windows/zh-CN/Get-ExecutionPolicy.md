+++
summary = "查看 PowerShell 脚本执行策略。"
+++
---

## 用途

查看 PowerShell 脚本执行策略。

## 基本语法

```powershell
Get-ExecutionPolicy [选项]
```

## 常用参数

- `-List`：显示各作用域策略。
- `-Scope`：查看指定作用域。

## 常用示例

```powershell
Get-ExecutionPolicy
Get-ExecutionPolicy -List
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Get-ExecutionPolicy -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-executionpolicy/)。
