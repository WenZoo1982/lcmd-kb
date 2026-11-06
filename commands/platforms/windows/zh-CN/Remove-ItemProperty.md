+++
summary = "删除文件、注册表等项的属性。"
+++
---

## 用途

删除文件、注册表等项的属性。

## 基本语法

```powershell
Remove-ItemProperty [-Path] 路径 [-Name] 属性 [选项]
```

## 常用参数

- `-Name`：指定要删除的属性。
- `-Force`：删除受限制属性（适用时）。
- `-WhatIf`：预览操作。

## 常用示例

```powershell
Remove-ItemProperty -Path 'HKCU:\Environment' -Name DemoValue -WhatIf
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Remove-ItemProperty -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/remove-itemproperty/)。
