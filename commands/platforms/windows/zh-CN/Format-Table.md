+++
summary = "以表格形式显示对象。"
+++
---

## 用途

以表格形式显示对象。

## 基本语法

```powershell
对象 | Format-Table [属性] [选项]
```

## 常用参数

- `-AutoSize`：根据内容调整列宽。
- `-Wrap`：允许单元格内容换行。
- `-Property`：指定显示属性。

## 常用示例

```powershell
Get-Process | Format-Table Name,Id,CPU -AutoSize
Get-Service | Format-Table -AutoSize
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Format-Table -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/format-table/)。
