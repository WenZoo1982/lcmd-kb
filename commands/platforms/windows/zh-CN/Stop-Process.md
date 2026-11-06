+++
summary = "停止一个或多个进程。"
+++
---

## 用途

停止一个或多个进程。

## 基本语法

```powershell
Stop-Process [-Name] 名称 [选项]
```

## 常用参数

- `-Id`：按进程 ID 指定目标。
- `-Force`：强制停止进程。
- `-PassThru`：返回进程对象。
- `-WhatIf`：预览操作。

## 常用示例

```powershell
Stop-Process -Name notepad
Stop-Process -Id 1234 -WhatIf
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Stop-Process -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/stop-process/)。
