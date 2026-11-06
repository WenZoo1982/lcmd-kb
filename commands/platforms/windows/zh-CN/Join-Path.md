+++
summary = "使用路径分隔符组合路径片段。"
+++
---

## 用途

使用路径分隔符组合路径片段。

## 基本语法

```powershell
Join-Path [-Path] 父路径 [-ChildPath] 子路径
```

## 常用参数

- `-Path`：父路径。
- `-ChildPath`：子路径。
- `-Resolve`：解析并返回实际存在的路径。

## 常用示例

```powershell
Join-Path C:\Logs app.log
Join-Path $HOME Documents
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Join-Path -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/join-path/)。
