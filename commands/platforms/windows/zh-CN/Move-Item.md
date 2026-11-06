+++
summary = "移动或重命名文件、目录及其他项。"
+++
---

## 用途

移动或重命名文件、目录及其他项。

## 基本语法

```powershell
Move-Item [-Path] 源路径 [-Destination] 目标路径 [选项]
```

## 常用参数

- `-Force`：覆盖目标项（适用时）。
- `-WhatIf`：预览移动操作。
- `-PassThru`：返回移动后的对象。

## 常用示例

```powershell
Move-Item .\report.txt .\Archive\
Move-Item .\old-name.txt .\new-name.txt
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Move-Item -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/move-item/)。
