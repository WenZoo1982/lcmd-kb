+++
summary = "查看 PowerShell 驱动器。"
+++
---

## 用途

查看 PowerShell 驱动器。

## 基本语法

```powershell
Get-PSDrive [名称] [选项]
```

## 常用参数

- `-Name`：按驱动器名称筛选。
- `-PSProvider`：按提供程序筛选。
- `-Scope`：指定作用域。

## 常用示例

```powershell
Get-PSDrive
Get-PSDrive -PSProvider FileSystem
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Get-PSDrive -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-psdrive/)。
