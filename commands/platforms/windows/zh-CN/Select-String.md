+++
summary = "在文件或字符串中搜索文本和正则表达式。"
+++
---

## 用途

在文件或字符串中搜索文本和正则表达式。

## 基本语法

```powershell
Select-String [-Pattern] 模式 [-Path] 路径 [选项]
```

## 常用参数

- `-Pattern`：指定文本或正则表达式。
- `-SimpleMatch`：按普通文本匹配。
- `-CaseSensitive`：区分大小写。
- `-Context`：显示匹配行前后的内容。
- `-AllMatches`：显示一行中的所有匹配项。

## 常用示例

```powershell
Select-String -Path .\*.log -Pattern 'error'
Get-Content .\app.log | Select-String 'timeout' -Context 2,2
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help Select-String -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/select-string/)。
