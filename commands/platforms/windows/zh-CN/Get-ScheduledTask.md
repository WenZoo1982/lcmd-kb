+++
summary = "查看 Windows 计划任务。"
+++
---

## 用途

查看 Windows 计划任务。

## 基本语法

```powershell
Get-ScheduledTask [选项]
```

## 常用参数

- `-TaskName`：按任务名称筛选。
- `-TaskPath`：按任务路径筛选。
- `-TaskPath '\'`：查看根目录任务。

## 常用示例

```powershell
Get-ScheduledTask
Get-ScheduledTask -TaskName '*Update*'
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Get-ScheduledTask -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-scheduledtask/)。
