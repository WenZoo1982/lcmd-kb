+++
summary = "选择对象的属性或指定数量的对象。"
+++
---

## 用途

选择对象的属性或指定数量的对象。

## 基本语法

```powershell
对象 | Select-Object [选项]
```

## 常用参数

- `-Property`：选择属性。
- `-First` / `-Last`：选择开头或末尾对象。
- `-ExpandProperty`：展开指定属性。
- `-Unique`：返回唯一结果。

## 常用示例

```powershell
Get-Process | Select-Object -First 10 Name,Id,CPU
Get-Service | Select-Object -ExpandProperty Name
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Select-Object -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/select-object/)。
