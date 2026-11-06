+++
summary = "重新执行当前会话历史中的命令。"
+++
---

## 用途

重新执行当前会话历史中的命令。

## 基本语法

```powershell
Invoke-History [[-Id] 编号或范围]
```

## 常用参数

- `-Id`：指定历史编号或编号范围。

## 常用示例

```powershell
Get-History
Invoke-History -Id 12
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Invoke-History -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/invoke-history/)。
