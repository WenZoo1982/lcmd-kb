+++
summary = "向控制台显示信息，适合交互式提示。"
+++
---

## 用途

向控制台显示信息，适合交互式提示。

## 基本语法

```powershell
Write-Host [对象] [选项]
```

## 常用参数

- `-ForegroundColor`：设置前景色。
- `-BackgroundColor`：设置背景色。
- `-NoNewline`：不追加换行。

## 常用示例

```powershell
Write-Host '完成' -ForegroundColor Green
Write-Host '处理中...' -NoNewline
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Write-Host -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/write-host/)。
