+++
summary = "检查路径或提供程序项是否存在。"
+++
---

## 用途

检查路径或提供程序项是否存在。

## 基本语法

```powershell
Test-Path [-Path] 路径 [选项]
```

## 常用参数

- `-PathType`：检查 Leaf、Container 或 Any 类型。
- `-IsValid`：只检查路径语法是否有效。
- `-LiteralPath`：按字面路径检查。

## 常用示例

```powershell
Test-Path .\config.json
Test-Path C:\Windows -PathType Container
Test-Path 'HKLM:\Software'
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Test-Path -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/test-path/)。
