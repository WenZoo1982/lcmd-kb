+++
summary = "创建注册表或其他项的新属性。"
+++
---

## 用途

创建注册表或其他项的新属性。

## 基本语法

```powershell
New-ItemProperty [-Path] 路径 [-Name] 名称 [-Value] 值 [选项]
```

## 常用参数

- `-PropertyType`：指定注册表值类型，如 String、DWord、QWord。
- `-Force`：覆盖已有属性（适用时）。
- `-WhatIf`：预览操作。

## 常用示例

```powershell
New-ItemProperty -Path 'HKCU:\Environment' -Name DemoValue -Value 'Hello' -PropertyType String -WhatIf
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help New-ItemProperty -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/new-itemproperty/)。
