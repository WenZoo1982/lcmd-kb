+++
summary = "设置 PowerShell 脚本执行策略。"
+++
---

## 用途

设置 PowerShell 脚本执行策略。

## 基本语法

```powershell
Set-ExecutionPolicy [-ExecutionPolicy] 策略 [选项]
```

## 常用参数

- `-Scope`：指定作用域，如 CurrentUser、LocalMachine。
- `-Force`：不显示确认提示。
- `-WhatIf`：预览操作。

## 常用示例

```powershell
Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned
Get-ExecutionPolicy -List
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Set-ExecutionPolicy -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/set-executionpolicy/)。
