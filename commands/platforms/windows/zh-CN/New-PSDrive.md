+++
summary = "创建临时或持久的 PowerShell 驱动器。"
+++
---

## 用途

创建临时或持久的 PowerShell 驱动器。

## 基本语法

```powershell
New-PSDrive [-Name] 名称 [-PSProvider] 提供程序 [-Root] 根路径 [选项]
```

## 常用参数

- `-Persist`：创建持久网络映射驱动器（Windows，需满足条件）。
- `-Credential`：指定凭据。
- `-Scope`：指定作用域。

## 常用示例

```powershell
New-PSDrive -Name Data -PSProvider FileSystem -Root C:\Data
New-PSDrive -Name Z -PSProvider FileSystem -Root \\server\share -Persist
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help New-PSDrive -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/new-psdrive/)。
