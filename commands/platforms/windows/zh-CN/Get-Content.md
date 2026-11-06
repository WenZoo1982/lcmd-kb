+++
summary = "读取文件内容。"
+++
---

## 用途

读取文件内容。

## 基本语法

```powershell
Get-Content [-Path] 路径 [选项]
```

## 常用参数

- `-TotalCount`：读取开头指定行数。
- `-Tail`：读取末尾指定行数。
- `-Wait`：持续等待并输出新增内容。
- `-Raw`：将内容作为单个字符串读取。
- `-Encoding`：指定文本编码。

## 常用示例

```powershell
Get-Content .\app.log
Get-Content .\app.log -Tail 50
Get-Content .\app.log -Wait -Tail 20
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Get-Content -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/get-content/)。
