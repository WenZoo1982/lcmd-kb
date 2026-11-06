+++
summary = "以列表形式显示对象属性。"
+++
---

## 用途

以列表形式显示对象属性。

## 基本语法

```powershell
对象 | Format-List [属性] [选项]
```

## 常用参数

- `-Property`：指定显示属性。
- `-Force`：显示更多可用属性。
- `*`：显示所有属性。

## 常用示例

```powershell
Get-Process powershell | Format-List *
Get-Service Spooler | Format-List Name,Status
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Format-List -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/format-list/)。
