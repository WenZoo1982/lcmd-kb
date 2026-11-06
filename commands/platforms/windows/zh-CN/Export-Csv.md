+++
summary = "将对象导出为 CSV 文件。"
+++
---

## 用途

将对象导出为 CSV 文件。

## 基本语法

```powershell
对象 | Export-Csv [-Path] 文件 [选项]
```

## 常用参数

- `-NoTypeInformation`：不写入类型信息（Windows PowerShell 常用）。
- `-Delimiter`：指定分隔符。
- `-Append`：追加到现有文件。
- `-Encoding`：指定编码。

## 常用示例

```powershell
Get-Process | Select-Object Name,Id,CPU | Export-Csv .\processes.csv -NoTypeInformation -Encoding UTF8
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Export-Csv -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/export-csv/)。
