+++
summary = "提取路径的父目录、文件名或驱动器部分。"
+++
---

## 用途

提取路径的父目录、文件名或驱动器部分。

## 基本语法

```powershell
Split-Path [-Path] 路径 [选项]
```

## 常用参数

- `-Parent`：返回父目录。
- `-Leaf`：返回最后一段名称。
- `-Qualifier`：返回驱动器或限定符。
- `-Extension`：返回扩展名（版本支持情况不同）。

## 常用示例

```powershell
Split-Path C:\Logs\app.log -Parent
Split-Path C:\Logs\app.log -Leaf
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Split-Path -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/split-path/)。
