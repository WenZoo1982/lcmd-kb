+++
summary = "创建或修改变量。"
+++
---

## 用途

创建或修改变量。

## 基本语法

```powershell
Set-Variable [-Name] 名称 [-Value] 值 [选项]
```

## 常用参数

- `-Name`：变量名称。
- `-Value`：变量值。
- `-Option`：设置变量选项。
- `-Scope`：指定作用域。
- `-Force`：覆盖受保护变量（适用时）。

## 常用示例

```powershell
Set-Variable -Name AppMode -Value 'Test'
$AppMode
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Set-Variable -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/set-variable/)。
