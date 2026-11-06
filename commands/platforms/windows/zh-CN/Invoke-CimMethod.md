+++
summary = "调用 CIM 实例或类的方法。"
+++
---

## 用途

调用 CIM 实例或类的方法。

## 基本语法

```powershell
Invoke-CimMethod [-InputObject] 对象 [-MethodName] 方法 [选项]
```

## 常用参数

- `-MethodName`：指定要调用的方法。
- `-Arguments`：传入方法参数。
- `-ClassName`：指定 CIM 类。

## 常用示例

```powershell
$os = Get-CimInstance Win32_OperatingSystem
$os | Invoke-CimMethod -MethodName Reboot
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Invoke-CimMethod -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/invoke-cimmethod/)。
