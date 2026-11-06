+++
summary = "注册 Windows 计划任务（ScheduledTasks 模块）。"
+++
---

## 用途

注册 Windows 计划任务（ScheduledTasks 模块）。

## 基本语法

```powershell
Register-ScheduledTask [-TaskName] 名称 [选项]
```

## 常用参数

- `-Action`：指定任务动作。
- `-Trigger`：指定触发条件。
- `-User`：指定运行账户。
- `-RunLevel`：指定运行权限级别。

## 常用示例

```powershell
$action = New-ScheduledTaskAction -Execute 'notepad.exe'
$trigger = New-ScheduledTaskTrigger -Daily -At 9am
Register-ScheduledTask -TaskName 'OpenNotepadDaily' -Action $action -Trigger $trigger -WhatIf
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Register-ScheduledTask -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/register-scheduledtask/)。
