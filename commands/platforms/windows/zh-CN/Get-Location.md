+++
summary = "显示当前工作目录或提供程序位置。"
+++
---

## 用途

显示当前工作目录或提供程序位置。

## 基本语法

```powershell
Get-Location [选项]
```

## 常用参数

- `-PSDrive`：显示指定驱动器的位置。
- `-PSProvider`：按提供程序筛选。

## 常用示例

```powershell
Get-Location
Get-Location -PSDrive C
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Get-Location -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-location/)。
