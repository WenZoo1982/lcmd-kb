+++
summary = "按一个或多个属性排序对象。"
+++
---

## 用途

按一个或多个属性排序对象。

## 基本语法

```powershell
对象 | Sort-Object [[-Property] 属性] [选项]
```

## 常用参数

- `-Descending`：降序排列。
- `-Unique`：去除重复项。
- `-Top` / `-Bottom`：只取前几项或后几项（版本支持情况不同）。

## 常用示例

```powershell
Get-Process | Sort-Object CPU -Descending
Get-ChildItem | Sort-Object Length
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Sort-Object -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/sort-object/)。
