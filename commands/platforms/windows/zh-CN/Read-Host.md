+++
summary = "从控制台读取用户输入。"
+++
---

## 用途

从控制台读取用户输入。

## 基本语法

```powershell
Read-Host [-Prompt] 提示 [选项]
```

## 常用参数

- `-Prompt`：显示输入提示。
- `-AsSecureString`：以安全字符串读取敏感输入。

## 常用示例

```powershell
$name = Read-Host '请输入名称'
$secret = Read-Host '请输入密码' -AsSecureString
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Read-Host -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/read-host/)。
