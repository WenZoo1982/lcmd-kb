+++
summary = "获取当前日期和时间。"
+++
---

## 用途

获取当前日期和时间。

## 基本语法

```powershell
Get-Date [选项]
```

## 常用参数

- `-Format`：按格式字符串输出。
- `-UFormat`：使用 Unix 风格格式字符串。
- `-Date`：指定要格式化的日期时间。
- `-AsUTC`：转换为 UTC（版本支持情况不同）。

## 常用示例

```powershell
Get-Date
Get-Date -Format 'yyyy-MM-dd HH:mm:ss'
(Get-Date).AddDays(7)
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Get-Date -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-date/)。
