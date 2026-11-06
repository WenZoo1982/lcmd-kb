+++
summary = "查找可用命令，并查看命令类型和来源。"
+++
---

## 用途

查找可用命令，并查看命令类型和来源。

## 基本语法

```powershell
Get-Command [[-Name] 名称] [选项]
```

## 常用参数

- `-Name`：按名称或通配符查找。
- `-Module`：限定模块。
- `-CommandType`：限定命令类型。
- `-All`：显示同名的所有命令。

## 常用示例

```powershell
Get-Command Get-Process
Get-Command *service*
Get-Command -Module Microsoft.PowerShell.Management
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Get-Command -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-command/)。
