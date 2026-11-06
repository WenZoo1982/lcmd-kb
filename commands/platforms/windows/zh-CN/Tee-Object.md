+++
summary = "将管道数据同时保存到文件或变量，并继续传递。"
+++
---

## 用途

将管道数据同时保存到文件或变量，并继续传递。

## 基本语法

```powershell
对象 | Tee-Object [-FilePath] 文件 或 [-Variable] 变量
```

## 常用参数

- `-FilePath`：保存到文件。
- `-Variable`：保存到变量。
- `-Append`：追加到文件。

## 常用示例

```powershell
Get-Process | Tee-Object -FilePath .\processes.txt | Sort-Object CPU -Descending
Get-Service | Tee-Object -Variable services | Where-Object Status -eq Running
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Tee-Object -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/tee-object/)。
