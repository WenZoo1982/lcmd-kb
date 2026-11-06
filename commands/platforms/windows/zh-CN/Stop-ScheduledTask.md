+++
summary = "停止正在运行的计划任务。"
+++
---

## 用途

停止正在运行的计划任务。

## 基本语法

```powershell
Stop-ScheduledTask [-TaskName] 名称 [选项]
```

## 常用参数

- `-TaskName`：指定任务名称。
- `-TaskPath`：指定任务路径。

## 常用示例

```powershell
Stop-ScheduledTask -TaskName 'MyBackup'
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Stop-ScheduledTask -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/stop-scheduledtask/)。
