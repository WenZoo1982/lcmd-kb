+++
summary = "切换当前工作目录或提供程序位置。"
+++
---

## 用途

切换当前工作目录或提供程序位置。

## 基本语法

```powershell
Set-Location [[-Path] 路径]
```

## 常用参数

- `-Path`：指定目标路径。
- `-LiteralPath`：按字面路径处理，不解析通配符。
- `-PassThru`：返回位置对象。

## 常用示例

```powershell
Set-Location C:\Users
Set-Location ..
Set-Location Env:
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Set-Location -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/set-location/)。
