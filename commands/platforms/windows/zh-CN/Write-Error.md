+++
summary = "写入错误流，报告非终止错误。"
+++
---

## 用途

写入错误流，报告非终止错误。

## 基本语法

```powershell
Write-Error [-Message] 消息 [选项]
```

## 常用参数

- `-Message`：错误消息。
- `-ErrorId`：指定错误标识。
- `-Category`：指定错误类别。
- `-ErrorAction`：控制错误处理行为。

## 常用示例

```powershell
Write-Error '配置文件不存在'
Write-Error 'Invalid input' -ErrorAction Stop
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Write-Error -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/write-error/)。
