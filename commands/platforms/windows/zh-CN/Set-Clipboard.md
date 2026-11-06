+++
summary = "设置剪贴板内容。"
+++
---

## 用途

设置剪贴板内容。

## 基本语法

```powershell
对象 | Set-Clipboard [选项]
```

## 常用参数

- `-Value`：设置剪贴板内容。
- `-Append`：追加文本（适用版本）。

## 常用示例

```powershell
Set-Clipboard -Value 'Copied from PowerShell'
Get-Content .\note.txt | Set-Clipboard
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Set-Clipboard -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/set-clipboard/)。
