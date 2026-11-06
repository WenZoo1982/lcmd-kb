+++
summary = "从 CSV 文件导入对象。"
+++
---

## 用途

从 CSV 文件导入对象。

## 基本语法

```powershell
Import-Csv [-Path] 文件 [选项]
```

## 常用参数

- `-Delimiter`：指定分隔符。
- `-Header`：指定列名。
- `-Encoding`：指定编码。

## 常用示例

```powershell
$users = Import-Csv .\users.csv
$users | Select-Object Name,Email
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Import-Csv -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/import-csv/)。
