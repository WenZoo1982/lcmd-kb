+++
summary = "获取剪贴板文本或对象内容。"
+++
---

## 用途

获取剪贴板文本或对象内容。

## 基本语法

```powershell
Get-Clipboard [选项]
```

## 常用参数

- `-Format`：指定读取格式。
- `-Raw`：将文本作为单个字符串返回。

## 常用示例

```powershell
Get-Clipboard
Get-Clipboard -Raw
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Get-Clipboard -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-clipboard/)。
