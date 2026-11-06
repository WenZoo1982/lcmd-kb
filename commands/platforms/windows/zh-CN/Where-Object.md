+++
summary = "按条件筛选管道中的对象。"
+++
---

## 用途

按条件筛选管道中的对象。

## 基本语法

```powershell
对象 | Where-Object { 条件 }
```

## 常用参数

- `-FilterScript`：指定筛选脚本块。
- 简写比较语法：`Where-Object 属性 -比较运算符 值`。

## 常用示例

```powershell
Get-Process | Where-Object CPU -gt 10
Get-Service | Where-Object {$_.Status -eq 'Running'}
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Where-Object -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/where-object/)。
