+++
summary = "设置文件、注册表等项的属性值。"
+++
---

## 用途

设置文件、注册表等项的属性值。

## 基本语法

```powershell
Set-ItemProperty [-Path] 路径 [-Name] 属性 [-Value] 值
```

## 常用参数

- `-Name`：属性名称。
- `-Value`：新值。
- `-Type`：提供程序支持时指定属性类型。
- `-WhatIf`：预览操作。

## 常用示例

```powershell
Set-ItemProperty -Path 'HKCU:\Environment' -Name Demo -Value '1' -WhatIf
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Set-ItemProperty -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/set-itemproperty/)。
