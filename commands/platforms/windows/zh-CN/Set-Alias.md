+++
summary = "创建或修改命令别名。"
+++
---

## 用途

创建或修改命令别名。

## 基本语法

```powershell
Set-Alias [-Name] 别名 [-Value] 命令 [选项]
```

## 常用参数

- `-Name`：别名名称。
- `-Value`：目标命令。
- `-Scope`：指定作用域。
- `-Option`：设置别名选项。

## 常用示例

```powershell
Set-Alias -Name ll -Value Get-ChildItem
ll
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Set-Alias -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/set-alias/)。
