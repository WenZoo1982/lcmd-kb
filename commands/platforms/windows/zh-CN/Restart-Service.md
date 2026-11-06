+++
summary = "停止后重新启动服务。"
+++
---

## 用途

停止后重新启动服务。

## 基本语法

```powershell
Restart-Service [-Name] 名称 [选项]
```

## 常用参数

- `-Name`：指定服务名称。
- `-Force`：强制重启服务及依赖服务（谨慎使用）。
- `-PassThru`：返回服务对象。

## 常用示例

```powershell
Restart-Service -Name Spooler
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Restart-Service -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/restart-service/)。
