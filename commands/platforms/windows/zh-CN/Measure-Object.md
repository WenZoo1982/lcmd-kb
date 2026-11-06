+++
summary = "计算对象数量、数值总和、平均值、最大值和最小值。"
+++
---

## 用途

计算对象数量、数值总和、平均值、最大值和最小值。

## 基本语法

```powershell
对象 | Measure-Object [选项]
```

## 常用参数

- `-Property`：指定数值属性。
- `-Sum`：计算总和。
- `-Average`：计算平均值。
- `-Minimum` / `-Maximum`：计算最小值和最大值。

## 常用示例

```powershell
Get-ChildItem -File | Measure-Object
Get-Process | Measure-Object CPU -Sum -Average -Maximum
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Measure-Object -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/measure-object/)。
