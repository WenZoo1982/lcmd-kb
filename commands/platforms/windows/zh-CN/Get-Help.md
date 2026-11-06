+++
summary = "查看 cmdlet、函数、脚本和概念帮助。"
+++
---

## 用途

查看 cmdlet、函数、脚本和概念帮助。

## 基本语法

```powershell
Get-Help 名称 [选项]
```

## 常用参数

- `-Examples`：只查看示例。
- `-Full`：显示完整帮助。
- `-Detailed`：显示详细帮助。
- `-Online`：打开在线帮助（需要网络）。

## 常用示例

```powershell
Get-Help Get-Process
Get-Help Get-ChildItem -Examples
Get-Help Get-Content -Online
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Get-Help -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-help/)。
