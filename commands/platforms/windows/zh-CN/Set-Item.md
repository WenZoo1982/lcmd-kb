+++
summary = "设置文件系统以外提供程序项的值等。"
+++
---

## 用途

设置文件系统以外提供程序项的值等。

## 基本语法

```powershell
Set-Item [-Path] 路径 [-Value] 值 [选项]
```

## 常用参数

- `-Path`：指定项路径。
- `-Value`：设置新值。
- `-Force`：覆盖受限制项（适用时）。

## 常用示例

```powershell
Set-Item Env:APP_MODE 'Production'
Get-Item Env:APP_MODE
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Set-Item -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/set-item/)。
