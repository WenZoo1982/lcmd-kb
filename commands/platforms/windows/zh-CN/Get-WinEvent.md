+++
summary = "查询 Windows 事件日志，支持现代事件日志和筛选语法。"
+++
---

## 用途

查询 Windows 事件日志，支持现代事件日志和筛选语法。

## 基本语法

```powershell
Get-WinEvent [-LogName] 日志名 [选项]
```

## 常用参数

- `-LogName`：指定日志通道。
- `-FilterHashtable`：按哈希表条件筛选。
- `-FilterXPath`：使用 XPath 筛选。
- `-MaxEvents`：限制返回记录数。

## 常用示例

```powershell
Get-WinEvent -LogName System -MaxEvents 20
Get-WinEvent -FilterHashtable @{LogName='System'; Level=2} -MaxEvents 30
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Get-WinEvent -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-winevent/)。
