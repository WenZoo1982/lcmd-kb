+++
summary = "暂停脚本执行指定时间。"
+++
---

## 用途

暂停脚本执行指定时间。

## 基本语法

```powershell
Start-Sleep [-Seconds 秒数] 或 [-Milliseconds 毫秒]
```

## 常用参数

- `-Seconds`：暂停秒数。
- `-Milliseconds`：暂停毫秒数。

## 常用示例

```powershell
Start-Sleep -Seconds 3
Start-Sleep -Milliseconds 500
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Start-Sleep -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/start-sleep/)。
