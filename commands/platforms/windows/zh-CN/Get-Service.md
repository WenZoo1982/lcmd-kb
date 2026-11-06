+++
summary = "获取本机服务信息。"
+++
---

## 用途

获取本机服务信息。

## 基本语法

```powershell
Get-Service [[-Name] 名称] [选项]
```

## 常用参数

- `-Name`：按服务名称筛选。
- `-DisplayName`：按显示名称筛选。
- `-DependentServices`：显示依赖服务。
- `-RequiredServices`：显示该服务依赖的服务。

## 常用示例

```powershell
Get-Service
Get-Service -Name Spooler
Get-Service | Where-Object Status -eq 'Running'
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Get-Service -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-service/)。
