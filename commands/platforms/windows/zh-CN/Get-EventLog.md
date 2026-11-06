+++
summary = "读取传统 Windows 事件日志。"
+++
---

## 用途

读取传统 Windows 事件日志。

## 基本语法

```powershell
Get-EventLog [-LogName] 日志名 [选项]
```

## 常用参数

- `-Newest`：只读取最新指定数量的记录。
- `-EntryType`：按事件级别筛选。
- `-Source`：按来源筛选。
- `-After` / `-Before`：按时间筛选。

## 常用示例

```powershell
Get-EventLog -LogName System -Newest 20
Get-EventLog -LogName Application -EntryType Error -Newest 50
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Get-EventLog -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-eventlog/)。
