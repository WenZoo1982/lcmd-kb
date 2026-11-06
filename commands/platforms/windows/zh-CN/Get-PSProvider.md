+++
summary = "查看 PowerShell 提供程序及其功能。"
+++
---

## 用途

查看 PowerShell 提供程序及其功能。

## 基本语法

```powershell
Get-PSProvider [名称]
```

## 常用参数

- `-PSProvider`：按名称筛选提供程序。

## 常用示例

```powershell
Get-PSProvider
Get-PSProvider FileSystem
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Get-PSProvider -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-psprovider/)。
