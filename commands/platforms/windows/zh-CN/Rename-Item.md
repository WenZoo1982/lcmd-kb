+++
summary = "重命名文件、目录或其他项。"
+++
---

## 用途

重命名文件、目录或其他项。

## 基本语法

```powershell
Rename-Item [-Path] 路径 [-NewName] 新名称 [选项]
```

## 常用参数

- `-NewName`：指定新名称，不应包含目标目录路径。
- `-Force`：尝试重命名受限制的项。
- `-WhatIf`：预览操作。

## 常用示例

```powershell
Rename-Item .\draft.txt final.txt
Rename-Item .\OldFolder -NewName NewFolder
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Rename-Item -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/rename-item/)。
