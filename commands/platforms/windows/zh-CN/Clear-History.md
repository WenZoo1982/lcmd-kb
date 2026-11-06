+++
summary = "清除当前 PowerShell 会话的命令历史记录。"
+++
---

## 用途

清除当前 PowerShell 会话的命令历史记录。

## 基本语法

```powershell
Clear-History [选项]
```

## 常用参数

- `-Id`：清除指定编号。
- `-Count`：清除最近指定数量的记录。
- `-Newest`：与 Count 配合选择最新记录。

## 常用示例

```powershell
Clear-History
Clear-History -Count 10
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Clear-History -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/clear-history/)。
