+++
summary = "将对象保存为 PowerShell CLIXML 文件。"
+++
---

## 用途

将对象保存为 PowerShell CLIXML 文件。

## 基本语法

```powershell
对象 | Export-Clixml [-Path] 文件 [选项]
```

## 常用参数

- `-Path`：指定输出文件。
- `-Depth`：指定序列化深度。
- `-Encoding`：指定编码（版本支持情况不同）。

## 常用示例

```powershell
Get-Process | Select-Object -First 5 | Export-Clixml .\processes.xml
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Export-Clixml -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/export-clixml/)。
