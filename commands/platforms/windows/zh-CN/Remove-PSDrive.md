+++
summary = "删除当前会话中的 PowerShell 驱动器。"
+++
---

## 用途

删除当前会话中的 PowerShell 驱动器。

## 基本语法

```powershell
Remove-PSDrive [-Name] 名称 [选项]
```

## 常用参数

- `-Name`：指定驱动器名称。
- `-Force`：删除正在使用的驱动器（适用时）。

## 常用示例

```powershell
Remove-PSDrive -Name Data
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Remove-PSDrive -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/remove-psdrive/)。
