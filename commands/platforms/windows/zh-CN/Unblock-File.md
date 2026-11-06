+++
summary = "移除文件的下载来源阻止标记。"
+++
---

## 用途

移除文件的下载来源阻止标记。

## 基本语法

```powershell
Unblock-File [-Path] 文件 [选项]
```

## 常用参数

- `-Path`：指定文件。
- `-WhatIf`：预览操作。
- 仅应对来源可信且已检查的文件使用。

## 常用示例

```powershell
Unblock-File .\trusted-script.ps1
Get-Item .\trusted-script.ps1 -Stream Zone.Identifier
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Unblock-File -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/unblock-file/)。
