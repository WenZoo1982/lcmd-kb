+++
summary = "对管道中的每个对象执行操作。"
+++
---

## 用途

对管道中的每个对象执行操作。

## 基本语法

```powershell
对象 | ForEach-Object { 操作 }
```

## 常用参数

- `-Process`：对每个输入对象执行的处理脚本块。
- `-Begin` / `-End`：处理前和处理后执行脚本块。
- `-Parallel`：并行处理（PowerShell 7+）。

## 常用示例

```powershell
1..5 | ForEach-Object { $_ * 2 }
Get-Process | ForEach-Object ProcessName
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help ForEach-Object -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/foreach-object/)。
