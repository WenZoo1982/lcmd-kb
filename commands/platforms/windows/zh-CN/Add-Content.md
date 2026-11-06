+++
summary = "向文件或其他项追加内容。"
+++
---

## 用途

向文件或其他项追加内容。

## 基本语法

```powershell
Add-Content [-Path] 路径 [-Value] 内容 [选项]
```

## 常用参数

- `-Value`：追加的内容。
- `-Encoding`：指定编码。
- `-NoNewline`：不添加末尾换行。

## 常用示例

```powershell
Add-Content .\app.log 'Started'
Get-Content .\app.log -Tail 5
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Add-Content -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/add-content/)。
