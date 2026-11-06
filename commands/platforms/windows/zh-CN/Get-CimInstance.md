+++
summary = "获取 CIM/WMI 管理对象。"
+++
---

## 用途

获取 CIM/WMI 管理对象。

## 基本语法

```powershell
Get-CimInstance [-ClassName] 类名 [选项]
```

## 常用参数

- `-ClassName`：指定 CIM 类。
- `-ComputerName`：指定远程计算机（使用适用的远程连接方式）。
- `-Filter`：使用 WQL 筛选。
- `-Property`：只获取指定属性。

## 常用示例

```powershell
Get-CimInstance Win32_OperatingSystem
Get-CimInstance Win32_Process -Filter "Name='notepad.exe'"
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Get-CimInstance -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-ciminstance/)。
