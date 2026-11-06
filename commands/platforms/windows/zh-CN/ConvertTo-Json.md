+++
summary = "将对象转换为 JSON 字符串。"
+++
---

## 用途

将对象转换为 JSON 字符串。

## 基本语法

```powershell
对象 | ConvertTo-Json [选项]
```

## 常用参数

- `-Depth`：指定序列化嵌套深度。
- `-Compress`：移除多余空白。
- `-AsArray`：始终输出 JSON 数组（PowerShell 7+）。

## 常用示例

```powershell
$data = Get-Process | Select-Object -First 2 Name,Id
$data | ConvertTo-Json -Depth 3
```

## 更多参数

本文仅精选常见 PowerShell 使用场景中的高频参数。参数和行为可能随 PowerShell 版本、操作系统及模块版本变化；完整语法请运行 `Get-Help ConvertTo-Json -Full`，或查阅 [Microsoft Learn](https://learn.microsoft.com/powershell/module/microsoft.powershell.core/convertto-json/)。
