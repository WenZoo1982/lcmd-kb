+++
summary = "查看对象包含的属性、方法和事件。"
+++
---

## 用途

查看对象包含的属性、方法和事件。

## 基本语法

```powershell
对象 | Get-Member [选项]
```

## 常用参数

- `-MemberType`：筛选成员类型。
- `-Name`：按成员名称筛选。
- `-View`：选择成员视图。

## 常用示例

```powershell
Get-Process | Get-Member
Get-Service | Get-Member -MemberType Property
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Get-Member -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-member/)。
