+++
summary = "从 CLIXML 文件还原序列化对象。"
+++
---

## 用途

从 CLIXML 文件还原序列化对象。

## 基本语法

```powershell
Import-Clixml [-Path] 文件
```

## 常用参数

- `-Path`：指定 CLIXML 文件路径。

## 常用示例

```powershell
$items = Import-Clixml .\processes.xml
$items
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Import-Clixml -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/import-clixml/)。
