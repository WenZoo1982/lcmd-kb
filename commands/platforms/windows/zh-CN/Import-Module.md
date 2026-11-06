+++
summary = "将模块导入当前会话。"
+++
---

## 用途

将模块导入当前会话。

## 基本语法

```powershell
Import-Module [-Name] 模块 [选项]
```

## 常用参数

- `-Force`：重新导入模块。
- `-Global`：导入到全局会话状态（适用时）。
- `-Prefix`：为导入命令添加前缀。
- `-PassThru`：返回模块对象。

## 常用示例

```powershell
Import-Module Microsoft.PowerShell.Management
Import-Module .\MyTools.psm1 -Force
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Import-Module -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/import-module/)。
