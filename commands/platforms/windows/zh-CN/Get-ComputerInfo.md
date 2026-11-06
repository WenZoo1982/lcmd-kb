+++
summary = "获取操作系统和计算机硬件信息。"
+++
---

## 用途

获取操作系统和计算机硬件信息。

## 基本语法

```powershell
Get-ComputerInfo [选项]
```

## 常用参数

- `-Property`：只返回指定属性。

## 常用示例

```powershell
Get-ComputerInfo
Get-ComputerInfo -Property WindowsProductName,WindowsVersion,OsBuildNumber
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Get-ComputerInfo -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-computerinfo/)。
