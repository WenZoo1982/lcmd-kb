+++
summary = "从已注册的 PowerShell 仓库安装模块。"
+++
---

## 用途

从已注册的 PowerShell 仓库安装模块。

## 基本语法

```powershell
Install-Module [-Name] 模块 [选项]
```

## 常用参数

- `-Scope CurrentUser`：只为当前用户安装。
- `-Repository`：指定仓库。
- `-RequiredVersion`：指定版本。
- `-Force`：跳过部分确认并强制安装。

## 常用示例

```powershell
Install-Module Pester -Scope CurrentUser
Install-Module PSReadLine -Scope CurrentUser
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Install-Module -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/install-module/)。
