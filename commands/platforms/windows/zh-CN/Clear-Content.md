+++
summary = "清空文件或其他项的内容，但保留项本身。"
+++
---

## 用途

清空文件或其他项的内容，但保留项本身。

## 基本语法

```powershell
Clear-Content [-Path] 路径 [选项]
```

## 常用参数

- `-Force`：清除受限制项的内容（适用时）。
- `-WhatIf`：预览操作。

## 常用示例

```powershell
Clear-Content .\app.log
Clear-Content .\*.tmp -WhatIf
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Clear-Content -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/clear-content/)。
