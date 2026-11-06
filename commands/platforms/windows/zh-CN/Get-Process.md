+++
summary = "获取本机正在运行的进程。"
+++
---

## 用途

获取本机正在运行的进程。

## 基本语法

```powershell
Get-Process [[-Name] 名称] [选项]
```

## 常用参数

- `-Name`：按进程名筛选。
- `-Id`：按进程 ID 筛选。
- `-IncludeUserName`：包含进程所属用户名（可能需要权限）。
- `-FileVersionInfo`：获取可执行文件版本信息。

## 常用示例

```powershell
Get-Process
Get-Process -Name chrome
Get-Process -Id 1234
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Get-Process -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-process/)。
