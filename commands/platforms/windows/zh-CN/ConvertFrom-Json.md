+++
summary = "将 JSON 字符串转换为 PowerShell 对象。"
+++
---

## 用途

将 JSON 字符串转换为 PowerShell 对象。

## 基本语法

```powershell
JSON字符串 | ConvertFrom-Json [选项]
```

## 常用参数

- `-AsHashtable`：转换为哈希表（版本支持情况不同）。
- `-NoEnumerate`：不枚举数组结果。

## 常用示例

```powershell
'{"name":"LCMD","version":"1.0"}' | ConvertFrom-Json
$data = Get-Content .\config.json -Raw | ConvertFrom-Json
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help ConvertFrom-Json -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/convertfrom-json/)。
