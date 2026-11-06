+++
summary = "查看当前 PowerShell 会话的命令历史。"
+++
---

## 用途

查看当前 PowerShell 会话的命令历史。

## 基本语法

```powershell
Get-History [选项]
```

## 常用参数

- `-Count`：限制显示数量。
- `-Id`：按历史记录编号筛选。

## 常用示例

```powershell
Get-History
Get-History -Count 20
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Get-History -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-history/)。
