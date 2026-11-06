+++
summary = "获取项的属性值，常用于注册表。"
+++
---

## 用途

获取项的属性值，常用于注册表。

## 基本语法

```powershell
Get-ItemProperty [-Path] 路径 [选项]
```

## 常用参数

- `-Name`：只获取指定属性。
- `-LiteralPath`：按字面路径处理。

## 常用示例

```powershell
Get-ItemProperty 'HKLM:\SOFTWARE\Microsoft\Windows NT\CurrentVersion'
Get-ItemProperty 'HKCU:\Environment'
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Get-ItemProperty -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-itemproperty/)。
